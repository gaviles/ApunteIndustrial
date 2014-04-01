Este es un proyecto con el objetivo de crear apuntes desde el punto de vista del estudiantado, para la carrera de ingeniería civil industrial.

Si deseas contactarme para agregar correcciones, o desear escribir un apunte para el proyecto visitame en: www.gaviles.com

====== Preambulo por defecto ======
\usepackage{tikz}
\usetikzlibrary{trees}
\usepackage{pgfplots}
\usepackage{pstricks}

===================================

%======== HEADER ==================
\usepackage{fancyhdr}
\pagestyle{fancy}
\lhead{\leftmark}
\rhead{\thepage}

===================================

%======== FOOTER =========
\cfoot{
\includegraphics[height=0.30in]{logo483x100.png}
 }
\rfoot{\thepage}

===================================

%======== LINES (ONLY ON HEADER) =========
\renewcommand{\headrulewidth}{0.4pt}

===================================

%======== DEFINES THE EMPTY STYLE ========
\fancypagestyle{plain}{
\cfoot{
\includegraphics[height=0.30in]{logo483x100.png}
 }
\rfoot{\thepage}
}
===================================

====== Activar gnuplot ============
tools-> preference -> File -> Handling Converters
	Selecionar: Latex(pdflatex) -> PDF(pdflatex)
	Convertidor: pdflatex -shell-escape $$i

===================================

====== Tipo de Documento ==========
document -> configuration -> Class of Documment
	Class of document: book (KOMA-Script)

==================================

====== Tipo de Documento ==========
document -> configuration -> Page design
	Format: Us letter
	Documento con dos caras: NO ACTIVO
	
==================================

===== Binarios de GNUPLOT ========
http://sourceforge.net/projects/gnuplot/files/gnuplot/testing%20%28pre-release%29%20binaries/

==================================

