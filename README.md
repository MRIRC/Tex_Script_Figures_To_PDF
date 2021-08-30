# Tex_Script_Figures_To_PDF
 Script to automatically add large number of figures to slides as PDF format
 
 1. Install MiKTeX: https://miktex.org/download
 
 
 2. Open PIDSAnalysis_results.tex using TeXworks
 
 3. Change the paths of the Figures inside to the ones in your computer:
 
\newcommand\SubImageER[3]{%
\includegraphics[width=#1\textwidth,height=#2\textwidth]{C:/Users/rcc/Documents/Projects/MRIRC/TexProgram_generate_slides/Tex_script_figures_to_pdf/Tex_Script_Figures_To_PDF/Figures/ERcoil/#3}
}

\newcommand\SubImage[3]{%
\includegraphics[width=#1\textwidth,height=#2\textwidth]{C:/Users/rcc/Documents/Projects/MRIRC/TexProgram_generate_slides/Tex_script_figures_to_pdf/Tex_Script_Figures_To_PDF/NoERcoil/#3}
}

 4. Run TeXworks.
 
 5. Install the missing packages when prompted to install them in MiKTeX.
 6. You should get the generated PDF.
 7. Enjoy!
