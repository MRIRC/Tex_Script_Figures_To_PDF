# Tex_Script_Figures_To_PDF
 Script to automatically add large number of figures to slides as PDF format
 
 Install MiKTeX: https://miktex.org/download
 
 
 Open PIDSAnalysis_results.tex.
 
 

 Download the figures in the folder Figures
 
 Change the paths of the Figures inside: 
 
\newcommand\SubImageER[3]{%
\includegraphics[width=#1\textwidth,height=#2\textwidth]{C:/Users/rcc/Documents/Projects/MRIRC/TexProgram_generate_slides/Tex_script_figures_to_pdf/Tex_Script_Figures_To_PDF/Figures/ERcoil/#3}
}

\newcommand\SubImage[3]{%
\includegraphics[width=#1\textwidth,height=#2\textwidth]{C:/Users/rcc/Documents/Projects/MRIRC/TexProgram_generate_slides/Tex_script_figures_to_pdf/Tex_Script_Figures_To_PDF/NoERcoil/#3}
}

 Run TeXworks.
 
 Install the missing packages when prompted to install them in MiKTeX.