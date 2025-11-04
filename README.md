<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=jagmohan123&show_icons=true&theme=tokyonight" height="160" alt="stats"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=jagmohan123&theme=tokyonight" height="160" alt="streak"/>
</p>
<p align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jagmohan123&layout=compact&theme=tokyonight" height="150" alt="top languages"/>
</p>

---

### ⚡ Fun Fact
> “Code. Debug. Repeat. 🚀”



Resume Code->
%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
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
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    {\Huge \scshape ABC Rai} \\ \vspace{1pt}
Belgum, Karnataka 591263 \\ \vspace{1pt}
    \small \raisebox{-0.1\height}\faPhone\ 9662346387 ~ \href{mailto:abc@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{abc@gmail.com}} ~ 
    \href{https://www.linkedin.com/in/abc@gmail//}{\raisebox{-0.2\height}\faLinkedin\ \underline{linkedin.com/in/abc-kanagale-26712a212}}  ~
    \href{https://github.com/kevali7826}{\raisebox{-0.2\height}\faGithub\ \underline{github.com/kevali7826}}
    \vspace{-8pt}
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStar
    \resumeSubheading
      {Techno India NJR Institute of Technology}{Sep. 2022 --Pursuing}
      {Bachelor of Technology in Computer Science {Percentage-9.42}}{Udaipur, Rajasthan}
  \resumeSubHeadingListEnd
    \resumeSubheading
      {G.I.Bagewadi college nippani }{May. 2019 --May. 2020}
      {Higher Secondary School}{Belgum, Karnatak}
  \resumeSubHeadingListEnd

%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
      \textbf{Programming Languages}{: C/C++, Java.} \\
     \textbf{Devops Tools }{: Git, Jenkins, Docker, Kubernetes, AWS, CI/CD, Terraform, Prometheus, Grafana.} \\
     \textbf{Frameworks \& Libraries}{: React.js, Node.js, Express.js, Tailwind CSS, Bootstrap.} \\
     \textbf{Databases and Subjects}{: MySQL, MongoDB, OPPS, DBMS.\\}
    \textbf{Developer Tools}{: Git, GitHub, Postman, Figma.\\}

 \end{itemize}
 \vspace{-16pt}


%-----------EXPERIENCE-----------
\section{Internship Experience}
  \resumeSubHeadingListStart

     \resumeSubheading
      {NJR}{March 2025 -- May 2025}
      {Devops Developer Intern}{Jaipur, Rajasthan}
      \resumeItemListStart
        \resumeItem{ Successfully completed a 60-day DevOps training program covering essential tools and practices for automation, CI/CD, and cloud deployment.}
        \resumeItem{Gained hands-on experience with tools like Git, Docker, Jenkins, Kubernetes, AWS for real-world DevOps workflows.}
        \resumeItem{Learned to automate software build, test, and deployment processes using CI/CD pipelines.}
        % \resumeItem{Worked with containerization (Docker) and orchestration (Kubernetes) to manage scalable applications.}
      \resumeItemListEnd

    \resumeSubheading
      {Grras}{Aug 2024 -- Oct 2024}
      {MERN Stack Developer Intern}{Jaipur, Rajasthan}
      \resumeItemListStart
        \resumeItem{Completed an intensive 90-day training program on the MERN Stack (MongoDB, Express.js, React.js, Node.js) with hands-on project development.}
        \resumeItem{Built full-stack web applications integrating front-end (React.js) and back-end (Node.js, Express) components with MongoDB databases..}
        \resumeItem{Gained practical experience in RESTful API development, authentication (JWT), and CRUD operations..}
        % \resumeItem{Collaborated on team projects using Git, GitHub, and Agile methodologies to simulate real-world development environments.}
      \resumeItemListEnd





  \resumeSubHeadingListEnd
\vspace{-16pt}

%-----------PROJECTS-----------
\section{Projects}
    \vspace{-5pt}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{DevOps CI/CD Pipeline Project} $|$ \emph{}}{May 2025}
          \resumeItemListStart
            \resumeItem{ Automated CI/CD pipeline using Jenkins to build, test, scan, and deploy Dockerized applications to Kubernetes.}
            \resumeItem{➡️Deployed apps using Kubernetes manifests with RBAC-based Jenkins access, ensuring secure and scalable deployment.}
            \resumeItem{➡️ Configured Prometheus and Grafana for real-time monitoring and visualization of system metrics and alerts.}
            \resumeItem{➡️Technology -: Jenkins, Git, Docker, Kubernetes, SonarQube, Trivy, Prometheus, and Grafana.}
          \resumeItemListEnd
          \vspace{-13pt}
      \resumeProjectHeading
          {\textbf{Shopping24} $|$ \emph{}}{July 2024}
          \resumeItemListStart
            \resumeItem{Designed and developed a fully functional Ecommerce web application from scratch, leveraging modern web technologies and following best practices (MVC architecture).}
            \resumeItem{ Implemented features such as account creation/update, profile management. Admin can create, edit, and delete categories, list items under specific categories, add items, and edit and delete items. Users can add items to a cart, buy items using Razorpay payment gateways, and view their order history.}
            \resumeItem{➡️ Implemented user authentication using JWT tokens, ensuring secure access to the web application.}
            \resumeItem{Technologies Used: React.js, Express.js, Node.js, MongoDB, Tailwind CSS.}
          \resumeItemListEnd
          \vspace{-13pt}
          \resumeProjectHeading


    \resumeSubHeadingListEnd
\vspace{-15pt}





%-----------INVOLVEMENT---------------
\section{Leadership / Extracurricular}
    \resumeSubHeadingListStart
        \resumeSubheading{Toastmaster Club Member }{April 2024 – Present}{Member}{Rajsthan Technical University}
            \resumeItemListStart
                \resumeItem{Hackathon Volunteer (2023) Actively participated as a volunteer in organizing a college hackathon event. Responsible for helping with logistics, participant coordination, and ensure smooth event flow.}
            \resumeItemListEnd
    \resumeSubHeadingListEnd
\end{document}
