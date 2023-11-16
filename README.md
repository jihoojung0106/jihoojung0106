%-------------------------
% Resume in Latex
% Author : Sourabh Bajaj
% Website: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[pdftex]{hyperref}
\usepackage{fancyhdr}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.375in}
\addtolength{\evensidemargin}{-0.375in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item\small{
    \textbf{#1}{: #2 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

\renewcommand{\labelitemii}{$\circ$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING-----------------
\begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
  \textbf{\href{http://sourabhbajaj.com/}{\Large Jihoo Jung}} & Email : \href{mailto:jjh123579@snu.ac.kr}{jjh123579@snu.ac.kr}\\
  \href{https://jihoojung0106.github.io/}{https://jihoojung0106.github.io} & Mobile : +82-10-7368-3405\\
\end{tabular*}


%-----------EDUCATION-----------------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Seoul National University}{Seoul, Korea}
      {BS in Economics, Computer Science;  GPA: 3.94/4.3}{Mar 2019 -- Present}
    
  \resumeSubHeadingListEnd


%-----------EXPERIENCE-----------------
\section{Work Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Beautiful Noise Inc.}{Seoul, Korea}
      {NFT Project Manager}{Nov 2021 - Aug 2022}
      \begin{itemize}
          \item Served as a pivotal team member within two international NFT projects, spearheading comprehensive project oversight and coordination.
    \end{itemize}

    \resumeSubheading
      {DeepTrade Technologies Corp.}{Seoul, Korea}
      {Mobile App Developer}{Jan 2023 - Mar 2023}
      \begin{itemize}
          \item Engaged as a Full Stack App Developer proficient in Django and React Native, responsible for crafting API architecture and enhancing application functionality.
    \end{itemize}

    \resumeSubheading
      {SNU Human-Computer Interaction Lab}{Seoul, Korea}
      {Research Intern}{Mar 2023 - Aug 2023}
      \begin{itemize}
          \item Participated in the development of AI-driven image recognition technology for extracting posture information from work motion videos.
    \end{itemize}

    \resumeSubheading
      {SNU Computing and Memory Architecture Laboratory}{Seoul, Korea}
      {Research Intern}{July 2023 - Present}
      \begin{itemize}
          \item Engaged in an in-depth investigation and research on the advanced field of neural radiance field.
    \end{itemize}

  \resumeSubHeadingListEnd


%-----------PROJECTS-----------------
\section{Projects}
  \resumeSubHeadingListStart
    \resumeSubItem{CT reconstruction}
      {Implemented and assessed the feasibility of a CPU-based FDK algorithm, incorporated the characteristics of the half-fan detector into the weighting process, and improved image quality through the application of diverse filter functions.}
    \resumeSubItem{Ambient AI}
      {Participated in the 2023 Summer Ambient AI BootCamp \& Competition at Seoul National University's Data Science Graduate School.}
    
    
  \resumeSubHeadingListEnd

%


%-----------REWARDS-----------------
\section{Awards}
\resumeSubHeadingListStart
  \resumeSubheading
    {Encouragement Prize, Thesis Contest}{}{Korea Deposit Insurance Corporation}{Oct 2021}
    \begin{itemize}
        \item Recognized for proposing a novel method to detect operational risks by analyzing time series private equity prices.
    \end{itemize}

  \resumeSubheading
    {Excellence Prize, Fintech Idea Contest}{}{Fintech Center Korea}{Sep 2023}
    \begin{itemize}
        \item Acknowledged for presenting a pioneering business concept that combines natural language processing and recommendation systems for an international stock trading platform.
    \end{itemize}
\resumeSubHeadingListEnd

%
%--------PROGRAMMING SKILLS------------
\section{English Skills}
 \resumeSubHeadingListStart
   \resumeSubheading
    {New Teps }{}{534/600}{Feb 2023}
    
 \resumeSubHeadingListEnd


%-------------------------------------------
\end{document}
