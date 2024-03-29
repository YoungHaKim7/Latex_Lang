# 요즘 잘나가는 typst (230609)

https://github.com/typst/typst

<hr>

# LaTex Tutorial

- LaTex Tutorial for Beginners Full Course

[https://youtu.be/fCzF5gDy60g](https://youtu.be/fCzF5gDy60g)

<br>

# LaTeX Learn LaTeX in 30 Minutes

https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes

<br>

# Windows OS Install LaTeX

LaTeX Tutorial 1 - Creating a LaTeX Document

https://youtu.be/qCgqYNhmmDE

<br>

# Windows OS 2

https://youtu.be/SoDv0qhyysQ

<br>

# MacTex Install

- https://tug.org/mactex/mactex-download.html

```
$ brew install mactex

$ brew install texlive

$ brew install --cask skim

$ brew search --cask tex-live-utility

```

https://vinitkumar.me/2019-01-16-Converting-Latex-to-PDF-on-macOS/

<br>

- How to proceed \_\_ LaTeXtoPDF

https://aty.sdsu.edu/bibliog/latex/LaTeXtoPDF.html

<br>

# LaTeX to PDF 1

1. mactex install

```
brew cask install mactex
```

2. main.tex 파일에서

```
$ pdflatex main.tex

```

3. ls 해보면

```
$ ls

build.sh  main.aux  main.out  main.tex

delete.sh main.log  main.pdf

```

- pdf 까지 다 나온다 mactex 최고

https://superuser.com/questions/1038612/where-do-i-get-the-pdflatex-program-for-mac

<br>

# LaTex Compile 2

```
$ latex latex.tex

latex.aux latex.dvi latex.log latex.out latex.tex
```

<br>

- skip.app 불러오기
- skip open latex.dvi 불러오기
- export PDF 하면 pdf 로 변환됨.

<br>

# LaTex Latex Overview

https://aty.sdsu.edu/bibliog/latex/latex_top.html

<br>

# CMT - Charlie's Math Template

https://github.com/SirCharlieMars/dotfiles/tree/master/latex_template

<br>

# LaTeX - Works with LaTeX

https://github.com/lambdasolver/LaTeX

<br>

# How I'm able to take notes in mathematics lectures using LaTeX and Vim

https://castel.dev/post/lecture-notes-1/#environments

<br>

# The differences between TeX engines

https://tex.stackexchange.com/questions/13593/the-differences-between-tex-engines

<br>

# LaTex Template 예제 파일

-

```
\documentclass[10pt,a4paper,sans]{moderncv}

% modern themes
\moderncvstyle{banking}                            % style options are 'casual' (default), 'classic', 'oldstyle' and 'banking'
\moderncvcolor{blue}                                % color options 'blue' (default), 'orange', 'green', 'red', 'purple', 'grey' and 'black'
%\renewcommand{\familydefault}{\sfdefault}         % to set the default font; use '\sfdefault' for the default sans serif font, '\rmdefault' for the default roman one, or any tex font name
%\nopagenumbers{}                                  % uncomment to suppress automatic page numbering for CVs longer than one page

% character encoding
\usepackage[utf8]{inputenc}                       % if you are not using xelatex ou lualatex, replace by the encoding you are using
%\usepackage{CJKutf8}                              % if you need to use CJK to typeset your resume in Chinese, Japanese or Korean
\usepackage{amsmath}

\usepackage{multicol}

% adjust the page margins
%\usepackage[scale=0.8]{geometry}
\usepackage[left=2cm, right=2cm, top=0.5cm]{geometry}
%\setlength{\hintscolumnwidth}{3cm}                % if you want to change the width of the column with the dates
%\setlength{\makecvheadnamewidth}{10cm}           % for the 'classic' style, if you want to force the width allocated to your name and avoid line breaks. be careful though, the length is normally calculated to avoid any overlap with your personal info; use this at your own typographical risks...

\usepackage{import}

% personal data
\name{Soham}{Chatterjee}
%% start of file `template.tex'.
%% Copyright 2006-2013 Xavier Danaux (xdanaux@gmail.com).
%
% This work may be distributed and/or modified under the
% conditions of the LaTeX Project Public License version 1.3c,
% available at http://www.latex-project.org/lppl/.


\documentclass[10pt,a4paper,sans]{moderncv}        % possible options include font size ('10pt', '11pt' and '12pt'), paper size ('a4paper', 'letterpaper', 'a5paper', 'legalpaper', 'executivepaper' and 'landscape') and font family ('sans' and 'roman')

% modern themes
\moderncvstyle{banking}                            % style options are 'casual' (default), 'classic', 'oldstyle' and 'banking'
\moderncvcolor{blue}                                % color options 'blue' (default), 'orange', 'green', 'red', 'purple', 'grey' and 'black'
%\renewcommand{\familydefault}{\sfdefault}         % to set the default font; use '\sfdefault' for the default sans serif font, '\rmdefault' for the default roman one, or any tex font name
%\nopagenumbers{}                                  % uncomment to suppress automatic page numbering for CVs longer than one page

% character encoding
\usepackage[utf8]{inputenc}                       % if you are not using xelatex ou lualatex, replace by the encoding you are using
%\usepackage{CJKutf8}                              % if you need to use CJK to typeset your resume in Chinese, Japanese or Korean
\usepackage{amsmath}

\usepackage{multicol}

% adjust the page margins
%\usepackage[scale=0.8]{geometry}
\usepackage[left=2cm, right=2cm, top=0.5cm]{geometry}
%\setlength{\hintscolumnwidth}{3cm}                % if you want to change the width of the column with the dates
%\setlength{\makecvheadnamewidth}{10cm}           % for the 'classic' style, if you want to force the width allocated to your name and avoid line breaks. be careful though, the length is normally calculated to avoid any overlap with your personal info; use this at your own typographical risks...

\usepackage{import}

% personal data
\name{Soham}{Chatterjee}

%\address{28, Rue Marcelin Berthelot, 92120 - Montrouge - France}% optional, remove / comment the line if not wanted; the "postcode city" and and "country" arguments can be omitted or provided empty
%\phone[mobile]{+919433548242}      % optional, remove / comment the line if not wanted
%\phone[fixed]{01234 123456}                    % optional, remove / comment the line if not wanted
%\phone[fax]{+3~(456)~789~012}                      % optional, remove / comment the line if not wanted
\email{sohamc@cmi.ac.in / sohamchatterjee999@gmail.com}                               % optional, remove / comment the line if not wanted
%\homepage{Brésilienne (Visa travail UE)}                         % optional, remove / comment the line if not wanted

\extrainfo{Date of Birth: 8th September, 2002}                % optional, remove / comment the line if not wanted
%\photo[64pt][0.4pt]{picture}                       % optional, remove / comment the line if not wanted; '64pt' is the height the picture must be resized to, 0.4pt is the thickness of the frame around it (put it to 0pt for no frame) and 'picture' is the name of the picture file
%\quote{Some quote}                                 % optional, remove / comment the line if not wanted

% to show numerical labels in the bibliography (default is to show no labels); only useful if you make citations in your resume
%\makeatletter
%\renewcommand*{\bibliographyitemlabel}{\@biblabel{\arabic{enumiv}}}
%\makeatother
%\renewcommand*{\bibliographyitemlabel}{[\arabic{enumiv}]}% CONSIDER REPLACING THE ABOVE BY THIS

% bibliography with mutiple entries
%\usepackage{multibib}
%\newcites{book,misc}{{Books},{Others}}
%----------------------------------------------------------------------------------
%            content
%----------------------------------------------------------------------------------
\begin{document}
	%\begin{CJK*}{UTF8}{gbsn}                          % to typeset your resume in Chinese using CJK
	%-----       resume       ---------------------------------------------------------
	\makecvtitle
	\vspace{-30pt}
	%{ \textbf{Expertise}: Marketing online et offline, Coordination des projets, Branding, Merchandising.\\
		%\textbf{Projets réalisés}:http://gnt.globo.com/especiais/projetos-multitelas}

	\section{Education}



	\begin{itemize}
		\item{\cventry{2021 -- Ongoing}{B. Sc - Mathematics and Computer Science}{Chennai Mathematical Institute}{Chennai, Tamilnadu, India}{}{
		}}
		\vspace{4pt}
		\item{\cventry{2020}{B. Tech 1st Year - Electronics and Communication Engineering}{University of Calcutta}{Kolkata, West Bengal, India}{}{
		}}

		\vspace{4pt}
		\item{\cventry{2018 -- 2020}{Higher Secondary ($12^{\text{th}}$ Standard)}{Baranagar Narendranath Vidyamandir}{Kolkata, West Bengal, India}{}{
		}}

		\vspace{4pt}

		\item{\cventry{2008 -- 2018}{Secondary ($10^{\text{th}}$ Standard)}{Baranagar Ramakrishna Mission Ashrama High School}{Kolkata, West Bengal, India}{}{
		}}


	\end{itemize}

	\section{Academic Achievements}



	\begin{itemize}

		\item{\cventry{2021}{Entrance exam of Chennai Mathematical Institute}{CMI Entrance}{Chennai Mathematical Institute}{}{}}

		\item{\cventry{2021}{Entrance exam of National Institute of Science Education and Research (NISER)}{NEST}{NISER}{}{}}

		\item{\cventry{2020}{West Bengal Joint Entrance Exam}{WBJEE - Rank 1893}{WBJEEB}{}{}}
		\item{\cventry{2020}{C R Rao Advanced Institute of Mathematics, Statistics and Computer Science (AIMSCS)}{12th Statistics Olympiad - Rank 108}{AIMSCS}{}{}}

	\end{itemize}

	\section{Reading Projects}
		\begin{itemize}
			\item \textbf{Ramanujan's work on theta functions and $q$-series and their connections with number theory.}

			\hfill Under Professor Rupam Barman, IIT Guahati during the summer break in May -- Jul, 2022.
		\end{itemize}

	\section{Courses}



	\begin{itemize}
		\begin{multicols}{2}

			\item \textbf{1st Semester (2021 Sept - Nov):} \begin{itemize}
				\item Analysis I
				\item Algebra I
				\item Classical Mechanics I
				\item Functional Programming in Haskell
				\item English
			\end{itemize}

			\item \textbf{2nd Semester (2022 Jan - Apr):} \begin{itemize}
				\item Analysis II
				\item Algebra II
				\item Probability
				\item Discrete Mathematics
				\item Advanced Programming in Python
			\end{itemize}

		\end{multicols}

		\item \textbf{3rd Semester (2022 Aug - Nov):} \begin{itemize}
			\item Analysis III
			\item Algebra III
			\item Design and Analysis of Algorithms
			\item Theory of Computation
			\item Calculus
		\end{itemize}

	\end{itemize}



	\section{Computer Skills}

	\begin{itemize}

		\item \textbf{Programming Languages:} Python, Haskell, Unix/Linux Shell Scripting

		\item \textbf{Technical Skills:} \LaTeX, Git, Github, Basic works in terminal, VIM


	\end{itemize}
	\section{Hobbies}

	\begin{itemize}

		\item  Watch Anime, Listen Music, Theming linux desktop


	\end{itemize}
	% Publications from a BibTeX file without multibib
	%  for numerical labels: \renewcommand{\bibliographyitemlabel}{\@biblabel{\arabic{enumiv}}}% CONSIDER MERGING WITH PREAMBLE PART
	%  to redefine the heading string ("Publications"): \renewcommand{\refname}{Articles}
%	\nocite{*}
%	\bibliographystyle{plain}
%	\bibliography{publications}                        % 'publications' is the name of a BibTeX file

	% Publications from a BibTeX file using the multibib package
	%\section{Publications}
	%\nocitebook{book1,book2}
	%\bibliographystylebook{plain}
	%\bibliographybook{publications}                   % 'publications' is the name of a BibTeX file
	%\nocitemisc{misc1,misc2,misc3}
	%\bibliographystylemisc{plain}
	%\bibliographymisc{publications}                   % 'publications' is the name of a BibTeX file

	%-----       letter       ---------------------------------------------------------

\end{document}



```

# KTUG 한글 Latex 사용자 그룹

http://www.ktug.org/xe/

<br>
