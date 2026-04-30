---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams

%-------------------------
% Resume in Latex
% Author : Sourabh Bajaj
% License : MIT
%------------------------

\documentclass[letterpaper,10pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[pdftex]{hyperref}
\usepackage{fancyhdr}

\usepackage{multicol}
\usepackage{hyperref}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.375in}
\addtolength{\evensidemargin}{-0.375in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.3in}
\addtolength{\textheight}{0.7in}
%\addtolength{\voffset}{-.1in}

\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    filecolor=magenta,      
    urlcolor=cyan,
}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{0pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item\small{
    \textbf{#1}{: #2 \vspace{-2pt}}
  }
}

\newcommand{\resumeItemO}[2]{
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


\newcommand{\resumeSubheadingNew}[6]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
      \textit{\small#5} & \textit{\small #6} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubheadingThree}[8]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
      \textit{\small#5} & \textit{\small #6} \\
      \textit{\small#7} & \textit{\small #8} \\
    \end{tabular*}\vspace{-1pt}
}

\newcommand{\resumeSubheadingFive}[12]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & {#2} \\
      \textit{\small#3} & \textit{\small #4} \\
      \textit{\small#5} & \textit{\small #6} \\
      \textit{\small#7} & \textit{\small #8} \\
      \textit{\small#9} & \textit{\small #10} \\
      \textit{\small#11} & \textit{\small #12} \\
    \end{tabular*}\vspace{-1pt}
}

\newcommand{\resumeSubItemO}[2]{\resumeItemO{#1}{#2}\vspace{-4pt}}
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
  % \textbf{\href{http://sourabhbajaj.com/}{\Large Ali Ebrahimpour Boroojeny}} & Email : \href{mailto:aebrahimpour@colostate.edu}{aebrahimpour@colostate.edu}\\
  % \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-970-412-2786 \\
  
  \textbf{\Large Zahra Borhani} & Email: \href{mailto:ali.ebrahimpour@columbia.edu}{zahra.borhani@colostate.edu}\\
  %& \href{mailto:aebrahimpour@nygenome.org}{aebrahimpour@nygenome.org}\\
     & Mobile: +1-720-989-0072 %- \href{https://www.linkedin.com/in/ali-ebrahimpour/}{LinkedIn}\\
\end{tabular*}



%-----------EDUCATION-----------------
%\section{Education}
%  \resumeSubHeadingListStart
%    \resumeSubheadingNew
%      {Colorado State University}{Fort Collins, CO}
%      {Ph.D. in Computer Science (36 credits);  GPA: 3.935}{Aug. 2016 -- Dec. 2018}
%      {MS Thesis: \bf{GTED: Graph Traversal Edit Distance} - Supervised by Prof. Hamidreza Chitsaz}{}
%    \resumeSubheadingNew
%      {Isfahan University of Technology}{Isfahan, Iran}
%      {Bachelor of Engineering in Information Technology (140 credits + 16 extra);  GPA: 3.104}{Sep. 2010 -- Jun. 2016}
%      {Out of 156 credits, 31 (equivalent to a minor) is taken from Math department}{}
%  \resumeSubHeadingListEnd

\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheadingNew
      {Colorado State University (CSU)}{Fort Collins, CO}
      %{Ph.D. in Computer Science}{Spring 2024 (Expected)}
      %{Ph.D. in Computer Science}{2021-Current}
      {Ph.D. in Computer Science, Advisor: Francisco R. Ortega}{Fall 2020-Fall 2026}
      {Research Area: Interaction Modalities in Extended Reality}{}%{PhD Thesis: \bf{TBD} - Supervised by Dr. David Knowles}{}
    \resumeSubheadingNew
      {Colorado State University (CSU)}{Fort Collins, CO}
      {Master of Science in Computer Science, Advisor: Francisco R. Ortega}{May 2020}
      {Thesis: Using Gender Swap in VR for Increasing Empathy Against Stereotype Threats} {}
    \resumeSubheadingNew
      {Sharif University of Technology (SUT)}{Tehran, Iran}
      {Master of Engineering in Computer Engineering, Advisor: Alireza Ejlali}{June 2016}
      {Thesis: Data allocation for SPM on embedded multi-core systems to reduce WCET}{}
    %\resumeSubheading
     % {Test Scores}{}
      %{TOEFL: 113/120\space\space\space\space\space GRE-Quantitative Reasoning: 168 (95\%)}{}
  \resumeSubHeadingListEnd
  
\vspace{-7pt}

%--------------Interests--------------------
%\section{Area of Interest}
   % Machine Learning, Machine Learning Theory, Computational Biology
   %Machine Learning, Robustness, Computational Biology

%-------------------------------------------

  \resumeSubHeadingListEnd       
\vspace{-7pt}
%--------PROGRAMMING SKILLS------------
\section{Skills}
  \resumeSubHeadingListStart
  \setlength\itemsep{0em}
    \item{
      \textbf{Languages: }{C\#, Python, R, Blueprints, SQL, C++, C}
      % \hfill
      }
      \item{
      %\textbf{Tools and Libraries: }{PyTorch, Git, TensorFlow}
      \textbf{Tools and Frameworks: }{Unity Engine, Unreal Engine, Mixed Reality Toolkit, Open XR, Figma, Blender, AdobeFuse, Maya, SDK, Vuforia, SteamVR, Character Creator3}%, Ensembl API, Samtools, BWA, GMAP, HISAT, Minimap2}
      }
       \item{
       \textbf{Devices: }{HoloLens 2, HTC Vive, Oculus Quest/Rift, VR Ink, Vive Trackers, Logitech, Holo-Stylus, Leap Motion, kinect  
}%, 
    }
    
  \resumeSubHeadingListEnd

\vspace{-15pt}
%-----------EXPERIENCE-----------------
\section{Experience}
  \resumeSubHeadingListStart

  %\resumeSubheading
      %{Google LLC}{Sunnyvale, CA}
      %{PhD Software Engineering Intern}{May 2024 - Aug 2024}
      %\resumeItemListStart
      %  \resumeItem{Google Clouds}
          %{Working on unsupervised learning problems. As a member of the modeling team I worked on developing pipelines to analyze and compare the clustering methods and performed research on incremental alternatives. The main purpose of these clustering methods is to to capture a higher-level understanding of the user tasks to provide them with relevant and useful ads. - Supervised by  
      %    {Working on community detection in large networks.}
      %\resumeItemListEnd
  
  %\resumeSubheading
    %  {In-Situ, Inc.}{Fort Collins, CO}
    %  {Data Science Intern}{Jan 2021 - May 2021}
    %  \resumeItemListStart
    %    \resumeItem{Analytics Team}
    %      {Analyzing the time series data generated from waste or surface water to recognize patterns and build predictive models.}}
    %  \resumeItemListEnd
  
  
 %   \resumeSubheading
%      {University of Illinois, Urbana-Champaign}{Urbana, IL}
%      {Research Assistant}{Aug. 2021 - Present}
%      \resumeItemListStart
%        \resumeItem{Sinha Laboratory}
%          {Research on inferring co-localization of transcripts and understanding how this information can be utilized to generate further hypotheses about the cell - Supervised by \href{https://www.sinhalab.net/sinha-s-home}{\underline{Prof. Saurabh Sinha}}}
%      \resumeItemListEnd
  
  \resumeSubheading
    {Colorado State University}{Fort Collins, CO}
      {Graduate Research Assistant - HCI Research}{Jan 2019 - May 2026}
      \resumeItemListStart
        \resumeItem{Natural User Interaction (NUILab)}
          %{Working on topics relevant to robustness and generalization of deep neural networks through the lens of noisy algorithms' properties and spectrum analysis  - Supervised by 
          {Interaction Modalities in Extended Reality - Supervised by 
          \href{https://scholar.google.com/citations?user=AuBa0OAAAAAJ&hl=en}{\underline{Prof. Francisco R. Ortega}}
          \resumeItem{Tasks}{Developed immersive AR/VR environments using Unity, MRTK, Vuforia, Blender, and Autodesk Maya. Designed and conducted human-centered studies (N = 20–80+), including controlled experiments, surveys, and interviews, and analyzed both quantitative and qualitative data using statistical and thematic methods. Led end-to-end research cycles, from problem formulation and system development to evaluation and dissemination, resulting in peer-reviewed publications. Contributed to multiple grant proposals and led the preparation of several NSF technical reports. Mentored and supervised undergraduate and master’s students, guiding them through research design, implementation, and dissemination.}
 }

      
      \resumeItemListEnd

  \resumeSubheading
      {Ricoh USA}{Exton, PA}
      {Augmented Reality Developer Intern (extended due to strong performance)}{May 2022- Dec 2022}
      \resumeItemListStart
        \resumeItem{Digital Services and Solutions }
          %{Working on unsupervised learning problems. As a member of the modeling team I worked on developing pipelines to analyze and compare the clustering methods and performed research on incremental alternatives. The main purpose of these clustering methods is to to capture a higher-level understanding of the user tasks to provide them with relevant and useful ads. - Supervised by  
          { Augmented Reality Developer - Supervised by \href{https://www.ricoh-usa.com/en/insights/author/nicole-blohm}{\underline{Nicole Blohm}}}
\resumeItem{Tasks} {Developed a proof-of-concept mobile AR interface to improve workplace efficiency using the Vuforia and Unity game engines, along with barcode scanners; designed and evaluated the user experience and functionality of the application; and conducted research on the use of AR in insurance applications.}
          
          
      \resumeItemListEnd


    %\resumeSubheading
    %{Katana Graph}{New York City, NY}
    %  {AI Research Intern}{Jul 2021-Aug 2021}
    %  \resumeItemListStart
    %    \resumeItem{GNN for Medicine}
    %      {Using Graph Neural Networks on heterogeneous graphs for predicting the effectiveness of various treatments for cancer - Supervised by 
    %      \href{https://inside.mines.edu/~bwu/}{\underline{Prof. Bo Wu}}
    %      }
    %  \resumeItemListEnd
      
  \resumeSubheading
    {Sharif University of Technology}{Tehran, Iran}
      {Research Assistant}{Jun 2012 - Jun 2015}
      \resumeItemListStart
        \resumeItem{ Embedded Systems Research Laboratory (ESR-LAB)}
          {Worked  on embedded systems - Supervised by 
          \href{https://scholar.google.com/citations?user=H7G8s68AAAAJ&hl=en}{\underline{Prof. Alireza Ejlali}}
          }
      \resumeItemListEnd


%%- Developed a proof-of-concept AR mobile application for workplace use
%Conducted research on digital solutions for AR applications
%Attended meetings as the representative of Ricoh in meetings with external contractors
%Tested the final application in workplace settings and assisted with debugging
  %\resumeSubheading
  %  {Katana Graph}{Denver, CO}
  %    {Researcher Intern}{Jul 2021 - Aug 2021}
  %    \resumeItemListStart
  %      \resumeItem{Bioinformatics Team}
  %        { I worked on modeling different projects of pharmaceutical companies as learning problems on graphs and designing methods to solve them.
  %        }
  %    \resumeItemListEnd

  
  
     
    % \resumeSubheading
    %   {City University of New York (CUNY)}{New York, NY}
    %   {Research Assistant}{Jan. 2020 - Dec 2020}
    %   %{Research Assistant}{Jan. 2020 - May. 2020 and Aug 2020 - Dec 2020}
    %   \resumeItemListStart
    %     \resumeItem{Algorithmic Biology Laboratory}
    %       %{Research on multi-RNA interaction with the goal of finding evidence for simultaneous interactions and modeling this phenomena. This model will be used to filter out the falsely reported interaction (e.g., the ones that are captured due to proximity rather than a true interaction)  
    %       {Research on multi-RNA interaction - Supervised by \href{http://www.rosemarybraun.org/}{\underline{Dr. Rosemary Braun}}, presented two talks}
    %   \resumeItemListEnd

   
      %\vspace{3pt}
      %\begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      
      %\textit{Graduate Representative} & {2018-2019} \\
      %    \end{tabular*}\vspace{-5pt}

      %\resumeItemListStart
        %\resumeItem{Graduate Recruiting Committee}
          %{Planning on how to advertise the university to attract more students to apply for the graduate school and organizing programs for senior undergraduate students to make them interested in graduate programs}
      %\resumeItemListEnd
      

    % \resumeSubheading
    %   {Colorado State University}{Fort Collins, CO}
    %   {Trainee and Presenter}{Summer 2017}
    %   \resumeItemListStart
    %     \resumeItem{Q-bio Summer School}
    %     {Attended talks and classes arranged for researchers in quantitative biology, worked on a two-week-long project supervised by \href{http://www.rosemarybraun.org/}{\underline{Dr. Rosemary Braun}}, presented two talks}
    %   \resumeItemListEnd

   
      
  \resumeSubHeadingListEnd
%\vspace{-14 pt}



\section{In Progress}
    \resumeSubHeadingListStart

    % \item \underline{A. Ebrahimpour Boroojeny} and H. Sundaram \textbf{Scalable Machine Unlearning by Fine Tuning Lipschitz Models.} 

    % \item \underline{A. Ebrahimpour Boroojeny}{$^\ast $}, The-Anh Vu{$^\ast $}, Qiang Wu{$^\ast $}, \& Arindam Banerjee. \textbf{Stochastic Localization for Training Restricted Boltzmann Machine.}

    % \item \underline{A. Ebrahimpour Boroojeny*}, Zahra Borhani*, H. Sundaram, \& F.R. Ortega. \textbf{Automatic Annotation in XR Using History of Interactions}.



    % \item \underline{A. Ebrahimpour Boroojeny}, Y. Wang, \& H. Sundaram. \textbf{Using Data and Feature Attribution Models for Effective Class Unlearning.} %\textit{Submitting to ACM CCS 2024}.
   


\item  \underline{Borhani, Z.,}  Ebrahimpour Boroojeny, A., Ortega, F.R.~\textbf{Privacy Leakage in Collaborative AR Anntation Systems.}~\textit{submitting to TVCG journal 2025}.

\small \textbf{Summery:} This work examines privacy risks in collaborative XR environments, focusing on how user-created annotations (text and sketches) can reveal author identity even in anonymous settings. It introduces authorship attribution attacks that leverage style-based features, using embedding similarity for text and time-series analysis for hand-drawn inputs, to accurately infer creators based on prior data. To mitigate these risks, the study proposes lightweight privacy-preserving transformations, including paraphrasing and summarization via LLMs for text, and beautification techniques for sketches. Results show that these methods significantly reduce attribution accuracy while preserving the utility of annotations, offering practical, easily deployable privacy protections for XR systems.

\item Gaddy, V., \underline{Borhani, Z.,}, and Ortega, F.R. \textbf{Implementing Novice-Expert Pair Coaching in Intermediate Level CS Recitations.}~\textit{submitting to The ACM Virtual Global Computing Education Conference 2026}.

\small \textbf{Summery:} This work evaluates a novice-expert pair coaching (NEPC) approach designed to support intermediate-level computer science students in a challenging software development course. Across two studies over 1.5 semesters, results show that NEPC can positively influence academic and psychological outcomes without harming learning. However, its benefits are more pronounced for developing programming and engineering skills than for improving performance in areas like mathematics or test-taking.

    \item  \underline{Borhani Z.,} Coler, A., Blanchard, N., Mastorakis, S., Shannigrahi , S., Szafir  D., Khadka , V., and Ortega F.~\textbf{Workshop on Distributed Interactive Systems for Collaboration Experiences (DISCE): Surveys}.~\textit{Under submission}.

\small \textbf{Summery:} This work explores the current state, challenges, and requirements of collaborative AR/VR systems through three surveys which was distributed during DISCE workshop which the authors of this paper held. It highlights key issues such as networking limitations (latency, reliability), lack of scalable tools, and the need for better interaction and infrastructure support. The findings emphasize the importance of hybrid systems, low-latency communication, and open, flexible platforms, while also noting the growing potential of machine learning to enhance XR collaboration.

   % \item \underline{A. Ebrahimpour Boroojeny}, V. Chandrasekaran, \& H. Sundaram. \textbf{AMUN: Adversarial Machine Unlearning.} \textit{under review at ICML 2025}.

    % \item \underline{A. Ebrahimpour Boroojeny}, H. Sundaram, \& V. Chandrasekaran. \textbf{DPO with Perturbed Prompts for Unlearning in LLMs.}

    % \item \underline{A. Ebrahimpour Boroojeny} \& V. Chandrasekaran. \textbf{Orthogonalized Convolutions for Multi-task Learning in LLMs.}




%-----------PROJECTS-----------------
\section{Under Review}
    \resumeSubHeadingListStart

    % \item \underline{A. Ebrahimpour Boroojeny} and H. Sundaram \textbf{Scalable Machine Unlearning by Fine Tuning Lipschitz Models.} 

    % \item \underline{A. Ebrahimpour Boroojeny}{$^\ast $}, The-Anh Vu{$^\ast $}, Qiang Wu{$^\ast $}, \& Arindam Banerjee. \textbf{Stochastic Localization for Training Restricted Boltzmann Machine.}

    % \item \underline{A. Ebrahimpour Boroojeny*}, Zahra Borhani*, H. Sundaram, \& F.R. Ortega. \textbf{Automatic Annotation in XR Using History of Interactions}.



    % \item \underline{A. Ebrahimpour Boroojeny}, Y. Wang, \& H. Sundaram. \textbf{Using Data and Feature Attribution Models for Effective Class Unlearning.} %\textit{Submitting to ACM CCS 2024}.
 
   
   \item Raikawr, A., \underline{Borhani, Z.,} Plubst, L., Barreta, M., Batmaz, A., Ortega, F.R.~\textbf{Beyond the Beep: Comparing Visual-Only and Multimodal Notification Design for Improved Noticeability in Augmented Reality.}~\textit{Under review in ISMAR 2026}.

    \small \textbf{Summery:} This study explores how different AR notification designs affect attention and performance, comparing multimodal (visual + audio) and visual-only approaches across four conditions in a simulated task environment. Results show no significant performance advantage for multimodal notifications over visual-only designs, and no clear improvement in attention capture or user preference. The findings suggest that well-designed visual notifications can be as effective as multimodal ones in some contexts, while highlighting the need for improved visual design and further research in more complex and noisy environments.
    
    \item Li, J.,\underline{Borhani, Z.,} Ortega, F.R.~\textbf{Multi-day Gesture Elicitation Study for Physical Simulation Learning Environments in Augmented and Virtual Reality.}~\textit{Under review in ISMAR 2026}.

    \small \textbf{Summery:} This study examines whether gestures elicited in Virtual Reality (VR) transfer to Augmented Reality (AR) by comparing user-defined gestures across 33 referents in a wind-simulation environment. Results show that gestures are largely consistent between AR and VR across most categories, with the exception of translation-based gestures, which differ due to their reliance on physical surfaces. These findings suggest strong cross-platform similarity while highlighting context-specific differences important for future gesture design in XR.


    \item Bukman, M.,~\underline{Borhani, Z.,}  Li, J., Ortega, F.R.\textbf{Does Virtual Reality Design Matter for Learning? A Study of Fluid Dynamics.}~\textit{Under review in ISMAR 2026}.
   % \item  \underline{Borhani Z.,} Coler, A., Blanchard, N., Mastorakis, S., Shannigrahi , S., Szafir  D., Khadka , V., and Ortega F.~\textbf{Workshop on Distributed Interactive Systems for Collaboration Experiences (DISCE): Surveys}.~\textit{Under submission}.


\small \textbf{Summery:} This project investigates whether Virtual Reality (VR) can enhance the teaching of complex and abstract physics concepts, specifically fluid dynamics, which are difficult to observe directly. By comparing traditional slide-based instruction with a combination of slides and a VR experience in a between-subjects study (N = 31), the project evaluates the impact of VR on students’ conceptual understanding. The findings indicate that students who received only traditional instruction outperformed those who used the additional VR module, suggesting that integrating VR does not necessarily improve learning outcomes and may introduce challenges that outweigh its potential benefits.

   % \item \underline{A. Ebrahimpour Boroojeny}, V. Chandrasekaran, \& H. Sundaram. \textbf{AMUN: Adversarial Machine Unlearning.} \textit{under review at ICML 2025}.

    % \item \underline{A. Ebrahimpour Boroojeny}, H. Sundaram, \& V. Chandrasekaran. \textbf{DPO with Perturbed Prompts for Unlearning in LLMs.}

    % \item \underline{A. Ebrahimpour Boroojeny} \& V. Chandrasekaran. \textbf{Orthogonalized Convolutions for Multi-task Learning in LLMs.}



  
\section{Publications}

%\textbf{Publication Summary:}


%2 journal, 2 conference, 2 arXiv, 2 workshop paper, 3 conference posters
  \resumeSubHeadingListStart
    % \resumeSubItem{GTED: Graph Traversal Edit Distance}
    %   {A new method to compute the similarity of two graphs. This method can be used as a graph kernel and is shown to be useful in various classification and clustering problems. \textit{(Accepted for RECOMB conference, 2018)}}
 \item \underline{Borhani, Z.,}  Holen, E.,
 Williams, A., Barrera-Machua, M., Batmaz, A., Kelley, B., Zhou, X., Rhodes, M, and Ortega, F.R.~\textbf{Recall This Gesture? Investigating Gesture Memorability in Augmented Reality.} \textit{In IEEE Transactions on Visualization and Computer Graphics (TVCG)}. 2026. (\href{https://ieeexplore.ieee.org/document/11457803}{link}).

\item \underline{Borhani, Z.,} Ebrahimpour Boroojeny, A., Ortega, F.R.~\textbf{Small Cues, Big Differences: Evaluating Interaction and Presentation for Annotation Retrieval in AR.}~\textit{Under review TVCG 2026}. (\href{https://arxiv.org/abs/2509.11401}{link}).

       \item \underline{Borhani, Z.,}  Delamarre, A., Hinzer, L., Ferguson, L., Jenkins, R., Barreto, A.,
 and Ortega, F.R.~\textbf{Comparing Instruction Methods for DailyBuddy: A Mobile App for Improving Daily Living Skills for Adults with Autism.}~\textit{In International Conference on Human-Computer Interaction (pp. 193-212).} 2025.  (\href{https://link.springer.com/chapter/10.1007/978-3-031-93061-4_13}{link}).

       \item Kroma, A., Scavarelli, A.,~\underline{Borhani, Z.,} Grinyer,K., Mcarthur, V.,
 and Ortega, F.R.~\textbf{3rd Workshop on Emerging Novel Prototyping Techniques for XR}~\textit{In 2025 IEEE Conference on Virtual Reality and 3D User Interfaces Abstracts and Workshops (VRW). IEEE.} 2025.  (\href{https://ieeexplore.ieee.org/abstract/document/10972780}{link}).  
 
   \item Ortega, F.R., Interrante, V., Lotemplio, S., Masters, R., Nicoly, J.,~\underline{Borhani, Z.,} Davalos, D. and  Zielasko, D.~\textbf{Enhancing Well-Being Through Positive Technology: VR Forest Bathing.}\textit{in PosiTech Workshop at ACM SIGCHI Conference on Computer-Supported Cooperative Work and Social Computing (CSCW) PosiTech Workshop}. 2024. (\href{https://arxiv.org/abs/2411.06293}{arXiv}).
    
    \item \underline{Borhani, Z.,} and Ortega, F.R.  \textbf{Enhancing Replicability in XR HCI Studies: A Survey-Based Approach}.~\textit{In 2024 IEEE International Symposium on Mixed and Augmented Reality Adjunct (ISMAR-Adjunct) (pp. 42-46). IEEE.} (\href{https://ieeexplore.ieee.org/abstract/document/10765306?casa_token=Up92RPq-XWUAAAAA:NDqzi6ieV0Szhh8JzVxxSVEJwc9Fl5pGQkTlMoQtyw5DG19hZ5_hYAbtePjwk3vPY7g1tEVbWjU}{link}).

       \item Li, J., Coler, A.,~\underline{Borhani, Z.,} and Ortega, F.R.  \textbf{Collecting and Analyzing the Mid-Air Gestures Data in Augmented Reality and User Preferences in Closed Elicitation Study}.~\textit{In International Conference on Human-Computer Interaction (pp. 201-215).} 2024. (\href{https://link.springer.com/chapter/10.1007/978-3-031-61044-8_15}{link}).

           
    \item \underline{Borhani, Z.,} Borhani, F., and Ortega, F.R.  \textbf{Experiencing Gravitational Red-Shifting in Virtual Reality}.~\textit{In IEEE Conference on Virtual Reality and 3D User Interfaces Abstracts and Workshops (VRW)}. 2024. (\href{https://ieeexplore.ieee.org/abstract/document/10536373}{link}).

     \item \underline{Borhani, Z.,} Sharma, P., and Ortega, F.R.  \textbf{A survey of Annotation in Extended Reality systems}.~\textit{In IEEE Transactions on Visualization and Computer Graphics (TVCG)}. 2024. (\href{https://ieeexplore.ieee.org/abstract/document/10160139}{Link}).

       \item \underline{Borhani, Z.,} and Ortega, F.R.  \textbf{A Virtual Reality System for Gender Swapping to Increase Empathy Against Stereotype Threats in Computer Science Job Interviews}.~\textit{ In IEEE International Symposium on Mixed and Augmented Reality Adjunct (ISMAR-Adjunct)}. 2023. (\href{https://ieeexplore.ieee.org/abstract/document/10322181}{link}).

     \item \underline{Borhani, Z.,} and Ortega, F.R.  \textbf{[DC] Annotation in Asynchronous Collaborative Immersive Analytic Environments using Augmented Reality}.~\textit{In IEEE conference on virtual reality and 3D user interfaces abstracts and workshops (VRW)}. 2022. (\href{https://ieeexplore.ieee.org/abstract/document/9757653}{link}).

 \item \underline{Borhani, Z.,} and Ortega, F.R.  \textbf{Using Gender Swap in Virtual Reality for Increasing Empathy Against Stereotype Threats}.~\textit{Master's thesis, Colorado State University}. 2020. (\href{https://www.proquest.com/openview/c8eaf2dfeef269cae04c3ba5de35714d/1?pq-origsite=gscholar&cbl=18750&diss=y}{link}).
     
   

    %   {Simulating the Nonlinear Systems. \textit{Submitted to Journal of Optimization Theory and Applications}}
    

    

    
 
    
    %\item {Ali Ebrahimpour Boroojeny, Akash Shrestha, Ali Sharifi-Zarchi, Suzanne Gallagher, S. Cenk Sahinalp, Hamidreza Chitsaz. \textbf{GTED: Graph Traversal Edit Distance}, Being submittd to Nature Communications journal, 2018}
    
     
    %\resumeSubItem{Error reduction of long genomic reads}
    %  {Using short accurate genomic sequences to correct genomic large reads with error rate up to 20\% using variaos string matching techniques such as MinHash, A*, and Needleman algorithm.}
    
    % \resumeSubItem{DP*}
    %   {An algorithm devised based on A* and Levenshtein distance for error-tolerant string matching.}
    
    % \resumeSubItem{Sentiment analysis of the highly tweeted names}
    %   {Using Apache Storm and the Lossy Counting algorithm to count and find the highly tweeted names from live Twitter message streams. Then, using Stanford’s NLP core APIs to do the sentiment analysis.}
  \resumeSubHeadingListEnd



%\section{Manuscripts in Preparation}
%  \resumeSubHeadingListStart
    % \resumeSubItem{GTED: Graph Traversal Edit Distance}
    %   {A new method to compute the similarity of two graphs. This method can be used as a graph kernel and is shown to be useful in various classification and clustering problems. \textit{(Accepted for RECOMB conference, 2018)}}
    
%    \item
%    {\underline{Ebrahimpour-Boroojeny, A. E.} \& Chitsaz, H. (2021). \textbf{SARS-CoV-2 orthologs of pathogenesis-involved small viral RNAs of SARS-CoV.}t arXiv preprint arXiv:2007.05859. (\href{https://arxiv.org/pdf/2007.05859.pdf}{Link})}
    
     
    
\resumeSubHeadingListEnd

%------------------Projects-----------------
%\section{Other Notable Projects}
  %\resumeSubHeadingListStart
    
    %\item {\textbf{DRRIP: Deep RNA-RNA Interaction Prediction:} We utilize fully connected and convolutional neural networks to predict if two RNAs interact with each other and where that interaction occurs. This work uses domain-specific features and vectorizations.}
    
  %\resumeSubHeadingListEnd
  
%------------------teaching-----------------
\section{Teaching Experience}
  %\resumeSubHeadingListStart
    \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{Colorado State University} & {\textbf{Fort Collins, CO}} \\
      \textit{\small \space\space Engaging in Virtual Worlds (CS462)} & \textit{\small Fall 2025} \\
      \textit{\small \space\space C++ Fundamentals (CT301)} & \textit{\small Summer 2025} \\
      \textit{\small \space\space Computer Organization (CS270)} & \textit{\small Spring 2018-Spring 2019} \\
      \textit{\small \space\space Database Systems (CS430)} & \textit{\small Summer 2019, Spring 2020, Summer 2020} \\
       \textit{\small \space\space Design Thinking Toolbox : Mixed Reality Design (CS/IDEA 310H)} & \textit{\small Fall 2020}\\
    \end{tabular*}\vspace{-1pt}
  
    \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{Sharif University of Technology} & {\textbf{Tehran, Iran}} \\
      % \textit{\small \space\space Introduction to Analysis of Algorithms (CS420)} & \textit{Fall 2016, Spring 2020} \\
      % \textit{\small \space\space Algorithms - Theory and Practice (CS320)} & \textit{\small Spring 2017 to Fall 2019 (6 semesters)} \\
      \textit{\small \space\space Lab Instructor of Logic Design (CS212) } & \textit{Fall 2013} \\
      \textit{\small \space\space Operations Management (MBA)} & \textit{\small Spring 2014} \\
    \end{tabular*}\vspace{-1pt}
    
    %     \vspace{-1pt}\item
    % \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
    %   \textbf{Isfahan University of Technology} & {\textbf{Isfahan, Iran}} \\
    %   \textit{\small \space\space Introduction to Artificial Intelligence} & \textit{\small Spring 2015, Fall 2015} \\
    % \end{tabular*}\vspace{-1pt}

\vspace{15pt}


%\section{Selected Courses}
%\vspace{-11pt}
%   \begin{multicols}{2}
%    \begin{itemize}
%        \item Artificial Intelligence (CS540): A
%        \vspace{-7pt}
%        \item Machine Learning (CS545): A
%        \vspace{-7pt}

%        \item Topological Data Analysis (Math580): A
%        \vspace{-5pt}
        % \item Software Product \& Process Evaluation (CS514): A
%        \item Bioinformatics Algorithms (CS445): A
%        \vspace{-5pt}
        
%    \end{itemize}
%    \end{multicols}
%\vspace{-15pt}



%\section{Languages}
%\vspace{-11pt}
%\begin{multicols}{2}
%\begin{itemize}
%    \item \textbf{English:} Fluent (TOEFL score: 113/120)
%    \item \textbf{Persian:} Native Language
%\end{itemize}
%\end{multicols}


%  \resumeSubHeadingListStart
%   \setlength\itemsep{0em}
%    \item{
%      \textbf{English: }{Proficient (TOEFL score: 113/120)}
%      \hss
%      \textbf{Persian: }{Native language}
%      }
%  \resumeSubHeadingListEnd
\vspace{-17pt}


\section{Honors and Awards}
\resumeSubHeadingListStart
  \setlength\itemsep{0em}
% \item Chosen as student representative in Graduate Recruiting Committee of CS department, CSU 2018-2019
 \item {Ranked $3^{rd}$ in ACM Graduate Research Competition, 2024 }. \href{https://compsci.colostate.edu/graduate-students/}{\color{tuftsblue}{\underline {News}}},~\href{https://drive.google.com/file/d/1V8dl7_RWi4o6IviwxIdgFO4mcx6MTF3g}{\color{tuftsblue}{\underline {Award}}}.

 %\item{ACM TAPIA Travel Scholarship Award: 2025, 2024, 2022, 2021, 2020.}
 %\item{Inclusion, Diversity, Equity and Accessibility Travel Scholarship, Sep 2021.}
%\item {Grace Hopper Celebration Student Travel Scholarship, Sep 2021}
 %\item {CMD-IT/ACM Richard Tapia Scholarship,  Mar 2021}
  %\item {ACM Tapia Scholarship, Sep 2020}
  \item {CS Excellence in Diversity Award, CSU, May 2020. }\href{https://drive.google.com/file/d/1s1-JKsg8aULmNwxHdVV-927j7lNl8H2O/view?usp=sharing}{\color{tuftsblue}{\underline {link}}}.
  \item {Ranked $1^{st}$ in CSU XR Hackathon competition, Fort Collins 2019}. \href{https://collegian.com/articles/news/2019/10/category-news-vr-meets-science-hackathon-births-vr-innovation/}{\color{tuftsblue}{\underline {link}}}.
 % \item {Fellowship for M.S. study, SUT, Tehran, Iran, 2012 - 2015 }
  \item { Ranked $35^{th}$ among 20,000+ participants, National M.Sc. Entrance Exam in Computer Architecture, Iran, 2012}


  
\section{Scholarships}
\resumeSubHeadingListStart
  \setlength\itemsep{0em}
% \item Chosen as student representative in Graduate Recruiting Committee of CS department, CSU 2018-2019
 %\item {Ranked $3^{rd}$ in ACM Graduate Research Competition, 2024 }. \href{https://compsci.colostate.edu/graduate-students/}{\color{tuftsblue}{\underline {News}}},~\href{https://drive.google.com/file/d/1V8dl7_RWi4o6IviwxIdgFO4mcx6MTF3g}{\color{tuftsblue}{\underline {Award}}}.

 \item{ACM TAPIA Travel Scholarship Award: 2025, 2024, 2022, 2021, 2020.}
 \item{Inclusion, Diversity, Equity and Accessibility Travel Scholarship, Sep 2021.}
\item {Grace Hopper Celebration Student Travel Scholarship, Sep 2021}
 %\item {CMD-IT/ACM Richard Tapia Scholarship,  Mar 2021}
  %\item {ACM Tapia Scholarship, Sep 2020}
  %\item {CS Excellence in Diversity Award, CSU, May 2020. }\href{https://drive.google.com/file/d/1s1-JKsg8aULmNwxHdVV-927j7lNl8H2O/view?usp=sharing}{\color{tuftsblue}{\underline {link}}}.
 % \item {Ranked $1^{st}$ in CSU XR Hackathon competition, Fort Collins 2019}. \href{https://collegian.com/articles/news/2019/10/category-news-vr-meets-science-hackathon-births-vr-innovation/}{\color{tuftsblue}{\underline{link}}}.
  \item {Fellowship for M.S. study, SUT, Tehran, Iran, 2012 - 2015 }
%  \item { Ranked $35^{th}$ among 20,000+ participants, National M.Sc. Entrance Exam in Computer Architecture, Iran, 2012}
  
%\item Gene Golub CS Fellowship, University of Illinois Urbana-Champaign, Urbana, IL 2021

%\item  Best Poster Award, Computer Science Graduate Research Symposium, Colorado State University, CO 2019

%\item Ranked $1^{st}$, XR/VR Hackathon, Colorado State University, CO 2019

%\item Best undergraduate GPA among all branches of Computer Science and Engineering, the academic year of 2014-2015, Isfahan University of Technology

%\item Ranked among the top 0.5\% in the national university entrance exam among +300,000 students and granted a fellowship to complete my undergraduate studies 

%\item Awarded $2^{nd}$ Honors Diploma from Russia Academy of Science, International Mathematical Tournament of Towns, Russia 2009

%\item Ranked $1^{st}$ among participating cities of Iran in Mathematical Tournament of Towns and awarded a scholarship (provided to the top $3$ teams) to participate in international competitions, Iran 2009

%\item Ranked $1^{st}$ in Isfahan province and $4^{th}$ nationwide in Khwarizmi robotic competitions, Iran 2009

%\item Ranked $3^{rd}$ nationwide in math Olympiad prep competitions, Iran 2007

%\item Member of National Organization for Development of Exceptional Talents (NODET), Iran, 2003-2010
\section{Conferences Attended}
HCI International 2025 (first-author conference paper presenter), ISMAR 2024 (first-author presenter of a TVCG journal article), IEEE VR 2024 (ENPTXR Workshop organizer and workshop paper presenter).
HCI International 2025 (first author conference paper presenter), ISMAR 2024 (TVCG journal first author presenter ),  IEEE VR 2024 (ENPTXR Workshop Organizer and workshop paper presenter), Tapia 2024 Conference (poster presenter), RMACC 2023, TAPIA 2022, IEEE VR (2022), RMACC 2022, TAPIA 2021, Grace Hopper 2021, TAPIA 2019


\section{Talks and Presentations}
\resumeSubHeadingListStart


\item  Presented the conference paper~\textit{``Instruction Methods for DailyBuddy: A Mobile App for Improving Daily Living Skills for Adults with Autism''} at the 27th International Conference on Human-Computer Interaction (HCII 2025). Gothenburg, Sweden (remote). June 25, 2025.

\item Presented the TVCG journal article~\textit{``A survey of Annotation in Extended Reality systems''} at the 23rd IEEE International Symposium on Mixed and Augmented Reality (ISMAR 2024). Seattle, USA. October 24, 2024.

\item Presented the workshop paper~\textit{``Enhancing Replicability in XR HCI Studies: A Survey-Based Approach''} at the 3rd Workshop on Replication in Extended Reality (WoRXR), ISMAR 2024. Seattle, USA. October 21, 2024.

\item Presented the poster~\textit{``A Mobile App for Improving Daily Living Skills for Adults with Autism''} at Tapia Conference. San Jose, USA. September 18-20, 2024.  (\href{https://docs.google.com/presentation/d/1Ng7INPHnn-W7FVtwoAJOhN-amv0DKbUS/edit?usp=sharing&ouid=117291499297435620006&rtpof=true&sd=true}{poster}).

\item Invited guest speaker at Dalhousie university (remote), presented \textit{``How to conduct a systematic literature review in Extended Reality''}. 

\item Presented the workshop paper~\textit{``Experiencing Gravitational Red-Shifting in Virtual Reality''} at the 31st IEEE Conference on Virtual Reality and 3D User Interfaces (IEEE VR 2024). Orlando, USA. March 17. (\href{https://docs.google.com/presentation/d/1fczZwvOYsQGtg-oI7m0AUAryCnBU6-pG/edit?usp=sharing&ouid=117291499297435620006&rtpof=true&sd=true}{slides}).

\item Presented the poster paper~\textit{``A Virtual Reality System for Gender Swapping to Increase Empathy
Against Stereotype Threats in Computer Science Job Interviews.''} at IEEE International Symposium on
Mixed and Augmented Reality Adjunct (ISMAR-Adjunct 2023). (\href{https://docs.google.com/presentation/d/1cmTs4NGvz-hUV0gtWFNd6_RAsePexzvM/edit?usp=sharing&ouid=117291499297435620006&rtpof=true&sd=true}{poster}). 



\item Presented the doctoral consortium paper~\textit{``Annotation in Asynchronous Collaborative Immersive Analytic Environments using Augmented Reality''} at In IEEE conference on virtual reality and 3D user interfaces abstracts and workshops (VRW 2024) (remote)


\section{Community Service}
\resumeSubHeadingListStart
  \setlength\itemsep{0em}
% \item Chosen as student representative in Graduate Recruiting Committee of CS department, CSU 2018-2019
\item {Reviewer at TVCG journal 2026 (1)}
\item {Registeration Co-Chair at SUI 2026}
\item {Reviewer at CHI 2026 (5)}
\item {Reviewer at TVCG journal 2025 (3)}
  \item {Registration Co-Chair at } \href{https://sui.acm.org/2025/committee-members/}{\underline {\color{tuftsblue}{{{SUI 2025}}}}}

  \item {Registration Co-Chair at } \href{https://vrst.acm.org/vrst2025/index.php/committee/}{\underline {\color{tuftsblue}{{{VRST 2025}}}}}

  \item {Organizing committee of } \href{https://www.xrprototyping.com/}{\underline {\color{tuftsblue}{{{ENPTXR Workshop at IEEE VR 2025}}}}}

 \item {Reviewer at ISMAR 2025} (3), {CHI 2025 (3)}

 \item {Organizing committee of } \href{https://www.xrprototyping.com/}{\underline {\color{tuftsblue}{{{ENPTXR Workshop at IEEE VR 2024}}}}}

 \item { Reviewer at GI 2024 (2), ISMAR 2024 (2), IEEE VR 2024 (1)}

\item {Organizing committee of  \textbf{}}\href{https://www.xrprototyping.com/} {\underline {\color{tuftsblue}{ ENPTXR at IEEE VR 2023}}}

\item {Reviewer at SUI 2023 (2), ISMAR 2023 (1)} 
 \item {Reviewer at Frontiers 2022 (2), ISMAR 2022 (1), ISS 2022 (1)}
  \item {Organizing committee of \textbf{}}  \href{https://sui.acm.org/2021-testing/}{\underline {\color{tuftsblue}{ACM SUI 2021}}}
  \item {Reviewer at ISMAR 2021 (2), IEEE VR 2021 (1), CHI LBW 2021 (1) }
  %\item {Organizing committee of "IEEE VR 2021 Workshop: Novel Input Devices and Interaction Techniques Workshop at IEEE VR 2021", March 2021}
%  \item {Web chair and publicity chair of "Next-Generation Networking Paradigms for Low Latency Applications Workshop at ACM CoNEXT, 2021}  \href{https://sites.google.com/view/ngnplla/home}{\underline {link}}
 \item {Organizing committee of \textbf{ }} \href{https://sites.google.com/view/disce}{\underline {\color{tuftsblue}{{DISCE at IEEE VR 2021}}}}
   \item {Organizing Committee of Graduate poster session, CS CSU, Spring 2019}
  % \item {Reviewer at \textbf{CHI 2021 Late-Breaking Work}}
 %  \item {Reviewer at \textbf{IEEE VR 2021}}
   \newline


\resumeSubHeadingListEnd

% \section{Hobbies}
% Photography, playing the guitar, watching films and reading what critics write about them, camping.




  %\resumeSubHeadingListEnd

%\section{Community Service}
%\resumeSubHeadingListStart

%\item {Vice President and Financial Officer of Iranian Students Organization, Colorado State University, Fall 2018 - Present}

%\item {Co-organized and hosted several university-wide celebrations of Iranian events, Colorado State University, 2018 - Present}

%\item {Graduate Recruiting Coordinator (GRC) at the Computer Science Department, Colorado State University, Fall 2018 - Spring 2019}

%\item {Co-organized a poster presentation session for newly admitted students, Computer Science Department at Colorado State University, Spring 2019}

%\resumeSubHeadingListEnd



%\section{Extracurricular Activities}

%\resumeSubHeadingListStart

%\item {Presented BPPart at WABI 2021}

%\item {Presented my master's thesis at qBio 2019 Conference}

%\item {My master's thesis was chosen to be presented at Graduate Student Showcase, Colorado State University, Fall 2017}

%\item {Attended Q-Bio Summer School, Colorado State University, June 2017. Also presented my research project and completed a pilot project under the supervision of Dr. Rosemary I Braun from Northeastern University.}

%\item {\textbf{Taking several online courses on Coursera (with awarded certificates):} \\Data Visualization: 100\% - Algorithms, Design and Analysis: 99\% - Algorithmic Thinking, part 1 and 2: 100\%, Principles of Computing part 1 and 2: 99\%, Bioinformatics I, II, and III: 98\%\\}
%(statements of accomplishment are available upon request)}

%\item {\textbf{Following many courses available online on YouTube and Coursera:} \\Fundamentals of Statistics (MIT), Algebraic Topology (UNSW), Bayesian Statistics (Ox educ), Neural Networks for Machine Learning (University of Toronto), Robotics: Estimation and Learning (UPenn), Multivariable Calculus (Khan Academy)\\}

% \item {\textbf{Following many courses available online on YouTube and Coursera:} \\Fundamentals of Statistics (MIT), Algebraic Topology (UNSW), Graph Theory and Additive Combinatorics (MIT), Bayesian Statistics (Ox educ), Neural Networks for Machine Learning (University of Toronto), Robotics: Estimation and Learning (UPenn), Quantum Computing (St. Petersburg State University), Multivariable Calculus (Khan Academy)\\}

%\resumeSubHeadingListEnd



%\section{Notable Academic Projects}
%\resumeSubHeadingListStart

%    \item {Using deep learning (e.g., Convolutional Neural Networks and Graph Neural Networks) along with representational learning techniques (e.g., Poincare embedding) to predict RNA-RNA interactions - Algorithmic Biology Laboratory }

%    \item {Using Graph Neural Networks for protein function prediction from heterogeneous protein-protein interaction networks - Graduate Independent Research course}
    

%    \item {Using Graph Neural Networks for Sybil detection in social networks - paid research at the IoT and Security lab in CSU}

%    \item {Error correction of noisy long reads by aligning them to assembly graphs of correct short reads using Minhash and a my new algorithm, DP*.}


%    \item {Evaluating variations of a group of Evolutionary Computing algorithms on fire-fighting drone problem (designed by me), which can be considered as a variation of the Traveling Salesman Problem (TSP) - Artificial Intelligence course}

    
%    \item {Implementing the Mismatch String Kernels for discriminative
%    protein classification and using that as a custom kernel in SVM to evaluate it on a protein classification dataset - Machine Learning course}
    
    % ... remaining content ...
\end{document}
