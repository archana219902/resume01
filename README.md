\documentclass[%singlesided,
doublesided,
paper=a4,
fontsize=10pt
]{my-resume}
\setlength\highlightwidth{8cm}
\setlength\headerheight{4cm}
\setlength\marginleft{1cm}
\setlength\marginright{\marginleft}    
\setlength\margintop{1cm}
\setlength\marginbottom{1cm}

%\RequirePackage{fontspec}
%\setmainfont{Carlito}

\colorlet{highlightbarcolor}{lightgray}
\colorlet{headerbarcolor}{darkgray}

\colorlet{headerfontcolor}{white}
\colorlet{accent}{awesome-red}
\colorlet{heading}{black}
\colorlet{emphasis}{black}
\colorlet{body}{black}




\begin{document}

\name{Mr. Fawzan Shajahan}
\tagline{Amazing tag line that makes HR managers want to hire you immediately.\\The tag line is aligned with the bottom of the picture to the right, so if \\you have multiple lines it fills the space to your name from the bottom.\\You might want to introduce manual line breaks to make this look nicer}
\photo[round]{pic.jpg}{\dimexpr \headerheight-\marginbottom}
\makeheader

\highlightbar{
    
    \section{Contact}
    \email{fawzanvs@gmail.com}  
    \phone{+91 97787 63784}
    \location{Thrissur, Kerala, India}
    \vspace{0.5em}
    
    \section{Skills}
    \skillsection{Programming}
    \skill{C/C++}{4}
    \skill{SQL}{4}
    \skill{Java}{3}
    \skill{HTML/CSS}{3}
    \skill{Python}{2}
    
    \vspace{0.5em}
    \skillsection{Operating Systems}
    \skill{Linux}{4}
    \skill{Windows}{4}
    
    \vspace{0.5em}
    \skillsection{Software \& Tools}
    \skill{Office}{4}
    
    \vspace{0.5em}
    \skillsection{Languages}
    \skill{English}{5}
    \skill{Malayalam}{5}
    \skill{Hindi}{3}
    \skill{Arabic}{2}
    \bigskip
    
    \section{Certificates}
    
}

\mainbar{
    
    \section[\faMortarBoard]{Education}
    \job{04/2016 - 05/2017}
        {Our Own High School Al-Warqa'a, Dubai}
        {Class X C.B.S.E}
        {CGPA: 9.0}
        
    \vspace{0.5em}
    \job{03/2018 - 04/2019}
        {Our Own High School Al-Warqa'a, Dubai}
        {Class XII C.B.S.E}
        {CGPA: 9.0}
        
    \vspace{0.5em}
    \job{09/2019 - 10/2021}
        {Bits Pilani Dubai Campus, Dubai}
        {B.Tech in CSE}
        {CGPA: 6.83}
    
    \vspace{0.5em}
    \job{12/2021 - Present}
        {Sahrdaya College of Engineering, Thrissur}
        {B.Tech in CSE}
        {}
        
    \section{Achievements, honours and awards}
    \achievement{My first achievement}
    \achievement{My second achievement}
    
    \section{General Skills}
    \smallskip % additional skip because tag outlines use up space
    \tag{Tag 1}
    \tag{Tag 2}
    \tag{and}
    \tag{another tag}
    \tag{some more tags}
    \tag{yet another one}
    \tag{tags flow over}
    \tag{to the next line}
    \tag{if necessary}
    
    \medskip
    
    \section{Wheel Chart}
    % This is taken from AltaCV
    % see https://github.com/liantze/AltaCV for details
    \wheelchart{1.5cm}{0.5cm}{% outer and inner diameter
        6/8em/accent!20/Sleep,          % comma-separated list of
        8/8em/accent!40/Daytime job,    % fraction of 24 / line length / color / label
        2/8em/accent!80/Training,          % here, the color is shades of the accent color
        3/8em/accent!60/Recovering from fighting criminals,
        5/8em/accent/Being Batman
    }
}

\makebody
\end{document}
