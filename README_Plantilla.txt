Esta plantilla es producto de adecuaciones técnicas de una versión proporcionada por alumnos del Departamento de Computación del CICESE y que se ha modificado por la Biblioteca con el fin de ofrecer una plantilla que se apegue de la mejor manera a los lineamientos. 

Actualizado el: 17 de julio de 2023.

LISTA DE PERSONAS QUE HAN COLABORADO EN LA ACTUALIZACIÓN DE ESTA PLANTILLA

DEPARTAMENTO		===		NOMBRE							
MCC					===		Alejandro Flores Lamas
MCC					===		Ana Karen Velázquez Sánchez
DC					===		Héctor Zatarain Aceves
MCC					===		Netzahualcóyotl Hernández Cruz
MCC					===		Darién Alberto Miranda Bojórquez
DC					===		Claudia Ivette García Gil
Biblioteca			===		Alma Lilia Nuñuez Rodríguez
Biblioteca			=== 	Oscar Peña Ramírez (opena@cicese.mx)

Instrucciones para el uso

1.	Se recomienda el uso de los editores:
a.	Windows: TeXnicCenter con la distribución de Latex Miketex.
b.		Multiplataforma: Texmaker con la distribución de Latex TexLive o Miketex (Windows).
c.	Overleaf: editor en línea (https://www.overleaf.com/)
2.	tesisCICESE.tex es el único archivo que se debe de compilar.
3.	La plantilla cuenta con los archivos para Resumen, Abstract, Dedicatoria, Agradecimientos, Literatura citada (literaturaTesis.bib), 5 Capitulos# y Anexos.
4.	Si se quiere agregar un capítulo más crear un archivo. tex dentro de la carpeta tesis_CICESE, y en tesisCICESE.tex agregar:
{\normalsize

\input{NombredeArchivo.tex}

\newpage}
, en la posición correspondiente a donde se quiere colocar el capítulo. Para los anexos no se requiere que se agreguen nuevos archivos, ya que todos los anexos deben de estar en un único archivo.
5.	Para citaren el texto se debe de utilizar los comandos \cite y \citep. Ejemplo:
\cite{Favela2007} %resultado Favela et al. (2007) \citep{CorderoEsquivel1988} %resultado (Cordero Esquivel, 1998)
6.	Puedes remplazar el archivo literaturaTesis.bib (Literatura citada) con tu propio archivo generado desde Mendeley o por ti. Nota: este archivo debe de mantener el nombre literaturaTesis.bib.
7.	Para generar correctamente la lista de literatura asegúrate que cada uno de los registros contenga al menos los mismos campos que el ejemplo que se tiene en el archivo literaturaTesisEjemplos.bib.
8.	Para que se muestren los cambios en el índice, en las citas y en la lista de literatura citada, es necesario compilar dos veces TesisCICESE.

9.	Se recomienda que las imágenes que se utilicen se coloquen en la carpeta Figures.
10.	En caso de que sea necesario modificar los espacios dentro de todo el documento se debe de editar el archivo tesisCICESE.tex. El espacio entre títulos de las secciones y el contenido se modifica en las líneas 83 a 85:
o	\titlespacing\section{0pt}{36pt plus 0pt minus 0pt}{18pt plus 0pt minus 2pt}
o	\titlespacing\subsection{0pt}{36pt plus 0pt minus 0pt}{18pt plus 0pt minus 0pt}
o	\titlespacing\subsubsection{0pt}{36pt plus 0pt minus 0pt}{18pt plus 0pt minus 0pt}

El espacio entre las figuras, tablas, ecuaciones y texto se modifica en las líneas 112 a 114:

o	\setlength{\textfloatsep}{18pt plus 1.0pt minus 1.0pt} 
o	\setlength{\intextsep}{18pt plus 1.0pt minus 1.0pt} 
o	%\setlength{\floatsep}{36pt plus 1.0pt minus 2.0pt}

Algunas páginas de utilidad al manejar LaTeX son:

	https://en.wikibooks.org/wiki/LaTeX
	https://tex.stackexchange.com/questions
	https://www.ctan.org
	https://tablesgenerator.com
