beamUSU 


1. Set \documentclass[aspectratio=169,12pt,xcolor={dvipsnames},mathserif]{beamer}
2. Set \title[short]{long}
3. Set \author{a and b}
--4. Set \institute{Utah State University}
5. Set \date{###}


Copy-Paste Opener:

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\documentclass[aspectratio=169,12pt,xcolor={dvipsnames},mathserif]{beamer}

\usepackage{beamUSU}

\title[ShortTitle]{Long Title}
\subtitle{subtitle}
\author{Landon Taylor}
\date{\today}

\begin{document}
\maketitle


\end{document}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


Easy Slide types:

One centered image: \image{image_url}
Two images: \images{url_left}{url_right}
Image + Text: \imagedesc{image_url}{text}
Two columns: \cols{col1}{col2}

Any other slide:
\begin{frame}{title}
	stuff
\end{frame}


In Landon's TexStudio:
Use CTRL+L to compile with LuaLatex