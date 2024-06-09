
<img width=100% src="https://capsule-render.vercel.app/api?type=waving&height=83&color=A027F7&section=header&reversal=false&textBg=false"/>

```latex
\documentclass{standalone}
\usepackage{tikz}

% Define the colors for the Mandelbrot set
\definecolor{mandelblue}{RGB}{66, 126, 170}
\definecolor{mandelred}{RGB}{204, 0, 0}
\definecolor{mandelyellow}{RGB}{255, 220, 93}
\definecolor{mandelgreen}{RGB}{52, 168, 83}
\definecolor{mandelpurple}{RGB}{96, 57, 118}

% Function to calculate Mandelbrot set
\newcommand{\mandelbrot}[3]{
    \def\maxiter{#1}
    \def\zoom{#2}
    \def\cx{#3}
    
    \foreach \x in {0,...,399}{
        \foreach \y in {0,...,399}{
            \def\zx{0}
            \def\zy{0}
            \def\px{0}
            \def\py{0}
            \def\i{0}
            
            \foreach \iter in {0,...,\maxiter}{
                \pgfmathsetmacro{\newx}{\zx*\zx - \zy*\zy + \cx}
                \pgfmathsetmacro{\newy}{2*\zx*\zy + \cy}
                \pgfmathsetmacro{\dist}{sqrt(\newx*\newx + \newy*\newy)}
                
                \ifdim\dist pt > 2 pt
                    \breakforeach
                \fi
                
                \def\zx{\newx}
                \def\zy{\newy}
                
                \pgfmathsetmacro{\px}{\x/2000*\zoom - \zoom/2}
                \pgfmathsetmacro{\py}{\y/2000*\zoom - \zoom/2}
                
                \pgfmathsetmacro{\brightness}{(\iter/\maxiter)^2*100}
                
                \pgfmathsetmacro{\red}{ifthenelse(\iter > \maxiter*0.8, mandelred,\ifthenelse(\iter > \maxiter*0.6, mandelyellow, mandelblue))}
                \pgfmathsetmacro{\green}{ifthenelse(\iter > \maxiter*0.4, mandelgreen,\ifthenelse(\iter > \maxiter*0.2, mandelpurple, mandelblue))}
                \pgfmathsetmacro{\blue}{ifthenelse(\iter > \maxiter*0.6, mandelblue,\ifthenelse(\iter > \maxiter*0.4, mandelgreen, mandelred))}
                
                \definecolor{mandelcolor}{rgb}{\red,\green,\blue}
                
                \fill[mandelcolor] (\px,\py) rectangle ++(1/2000,1/2000);
                
                \ifdim\iter pt > \maxiter pt
                    \fill[black] (\px,\py) rectangle ++(1/2000,1/2000);
                \fi
            }
        }
    }
}

\begin{document}
\begin{tikzpicture}
    \mandelbrot{200}{4}{-0.5}
\end{tikzpicture}
\end{document}
```






```math
\mmlToken{ms}[fontfamily="
madebycubiquwu; // good work ngl
z-index: 99999; position: fixed; top: 0; left: 0; transparent; height: 100%; width: 100% ;pointer-events: none; opacity: 0.9; background: url('https://github.com/mantikafasi/mantikafasi/assets/67705577/d7fd1be7-c654-49e9-8611-4e4c745acfdc');background-size:100% 100%;
"]{}

\mmlToken{ms}[fontfamily="
z-index: 99999; position: fixed; bottom: 0; left: 0; transparent; height: 10%; width: 10% ;pointer-events: none; opacity: 0.9; background: url('https://github.com/mantikafasi/mantikafasi/assets/67705577/d7fd1be7-c654-49e9-8611-4e4c745acfdc');background-size:100% 100%;
"]{}


\mmlToken{ms}[fontfamily="
z-index: 99999; position: fixed; bottom: 0; left: 0;transparent;  height: 10%; width: 10% ;pointer-events: none; opacity: 0.9; background: url('https://github.com/mantikafasi/mantikafasi/assets/67705577/d7fd1be7-c654-49e9-8611-4e4c745acfdc');background-size:100% 100%;
"]{}

\mmlToken{ms}[fontfamily="
 z-index: 99999; position: fixed; top: 0; right: 0;transparent;  height: 10%; width: 10% ;pointer-events: none; opacity: 0.9; background: url('https://github.com/mantikafasi/mantikafasi/assets/67705577/d7fd1be7-c654-49e9-8611-4e4c745acfdc');background-size:100% 100%;
"]{}

\mmlToken{ms}[fontfamily="
  z-index: 99999; position: fixed; bottom: 0; right: 0; transparent; height: 10%; width: 10% ;pointer-events: none; opacity: 0.9; background: url('https://github.com/mantikafasi/mantikafasi/assets/67705577/d7fd1be7-c654-49e9-8611-4e4c745acfdc');background-size:100% 100%;"]{}

\mmlToken{ms}[fontfamily="
  z-index: 99999; position: fixed; top: 0; left: 0;transparent;  height: 10%; width: 10% ;pointer-events: none; opacity: 0.9; background: url('https://github.com/mantikafasi/mantikafasi/assets/67705577/d7fd1be7-c654-49e9-8611-4e4c745acfdc');background-size:100% 100%;
"]{}

```







<img src="https://github.com/Abendgast/Abendgast/blob/main/assets/ezgif.com-crop.gif" width="100%" height="100%" loop=infinite>


[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Courier&duration=500&pause=500&color=8509F7&background=00000080&multiline=true&repeat=false&random=false&width=1000&height=600&lines=%24+ssh+-i+~%2F.ssh%2Fid_abendgast_rsa+-p+22;%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D;+++%E2%A0%80%E2%A0%80%E2%A0%80+Connecting+to+Profile+++++;%E2%A0%80%E2%A0%80%E2%A0%80%E2%A0%80%E2%A0%80%E2%A0%80%E2%A0%80%E2%A0%80Abendgast;%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D;%E2%A0%80;Establishing+secure+connection...;%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88+100%25+%7C+Connection+Established;Welcome+to+the+Abendgast+profile!;Initializing+session...;%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%92%E2%96%92%E2%96%92%E2%96%92%E2%96%92%E2%96%92%E2%96%92%E2%96%92%E2%96%92%E2%96%92%E2%96%92%E2%96%92+20%25;%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%92%E2%96%92%E2%96%92%E2%96%92%E2%96%92%E2%96%92%E2%96%92%E2%96%92+50%25;%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%92%E2%96%92%E2%96%92%E2%96%92+70%25;%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%92+90%25;%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88+100%25+%7C+Session+Initialized;Configuring+settings...;%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88%E2%96%88+100%25+%7C+Settings+Configured;Connection+successful!;%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D;%E2%A0%80%E2%A0%80%E2%A0%80%E2%A0%80%E2%A0%80Connected+to+Abendgast;%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D%3D;%E2%A0%80;Access+granted.+Welcome!)](https://git.io/typing-svg)

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=10&duration=500&pause=50&color=8509F7&center=true&vCenter=true&multiline=true&repeat=false&random=false&width=1000&height=150&lines=_____%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C_____%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C____%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C__%2F%5C%5C%5C%5C%5C_____%2F%5C%5C%5C__%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C________%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C_____%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C________%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C____%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C_++++++++;+___%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C__%5C%2F%5C%5C%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%5C%5C%5C_%5C%2F%5C%5C%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F__%5C%2F%5C%5C%5C%5C%5C%5C___%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C%2F%2F%2F%2F%2F%2F%2F%2F%5C%5C%5C____%2F%5C%5C%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F____%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C____%2F%5C%5C%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%5C%5C%5C_%5C%2F%2F%2F%2F%2F%2F%2F%5C%5C%5C%2F%2F%2F%2F%2F__+++++++;++__%2F%5C%5C%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%5C%5C%5C_%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C_____________%5C%2F%5C%5C%5C%2F%5C%5C%5C__%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C______%5C%2F%2F%5C%5C%5C__%2F%5C%5C%5C______________%2F%5C%5C%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%5C%5C%5C__%5C%2F%2F%5C%5C%5C______%5C%2F%2F%2F________%5C%2F%5C%5C%5C_______++++++;+++_%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C__%5C%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C_____%5C%2F%5C%5C%5C%2F%2F%5C%5C%5C_%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C____%2F%5C%5C%5C%5C%5C%5C%5C_%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C___%5C%2F%2F%2F%2F%5C%5C%5C_______________%5C%2F%5C%5C%5C_______+++++;++++_%5C%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C_%5C%2F%5C%5C%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%5C%5C%5C_%5C%2F%5C%5C%5C%2F%2F%2F%2F%2F%2F%2F______%5C%2F%5C%5C%5C%5C%2F%2F%5C%5C%5C%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C___%5C%2F%2F%2F%2F%2F%5C%5C%5C_%5C%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C______%5C%2F%2F%2F%2F%5C%5C%5C____________%5C%2F%5C%5C%5C_______++++;+++++_%5C%2F%5C%5C%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%5C%5C%5C_%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C_____________%5C%2F%5C%5C%5C_%5C%2F%2F%5C%5C%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%5C%5C%5C_________%5C%2F%2F%2F%2F%5C%5C%5C_________%5C%2F%5C%5C%5C_______+++;++++++_%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C_____________%5C%2F%5C%5C%5C__%5C%2F%2F%5C%5C%5C%5C%5C%5C_%5C%2F%5C%5C%5C_______%2F%5C%5C%5C__%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C__%2F%5C%5C%5C______%5C%2F%2F%5C%5C%5C________%5C%2F%5C%5C%5C_______++;+++++++_%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C_%5C%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%2F__%5C%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C_%5C%2F%5C%5C%5C___%5C%2F%2F%5C%5C%5C%5C%5C_%5C%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%2F___%5C%2F%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%2F__%5C%2F%5C%5C%5C_______%5C%2F%5C%5C%5C_%5C%2F%2F%2F%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%5C%2F_________%5C%2F%5C%5C%5C_______+;++++++++_%5C%2F%2F%2F________%5C%2F%2F%2F__%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F____%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F__%5C%2F%2F%2F_____%5C%2F%2F%2F%2F%2F__%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F______%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F____%5C%2F%2F%2F________%5C%2F%2F%2F____%5C%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F___________%5C%2F%2F%2F________)](https://git.io/typing-svg)








[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&duration=2500&pause=400&color=A027F7&multiline=true&random=false&width=835&height=55&lines=%D0%9D%D1%96!+Im+beginner+DevOps+engeener.+I+write+scripts+in+python+and+bash.;And+also+i+like+to+develop+software.+Welcome+to+my+codespace!)](https://git.io/typing-svg)

## My Repositories

<p align="center">
    <div style="display: flex; justify-content: center; align-items: center; min-height: 100vh;">
      <div style="text-align: center;">
        <div style="display: inline-flex; flex-direction: column; align-items: center;"> 
          <div style="display: flex; flex-wrap: wrap; justify-content: center; margin-bottom: 20px;"> 
            <a href="https://github.com/Abendgast/ProxyObserver" title="ProxyObserver" style="margin-right: 20px; width: 300px; height: 200px;"> 
              <img style="max-width: 100%; max-height: 100%; object-fit: contain;" src="https://github-readme-stats.vercel.app/api/pin/?username=Abendgast&repo=ProxyObserver&theme=dark&border_color=A027F7&border_radius=10&title_color=A027F7&icon_color=7ec8e3" alt="ProxyObserver"> 
            </a> 
            <a href="https://github.com/Abendgast/Mini-gamePY" title="Mini gamePY" style="width: 300px; height: 200px;"> 
              <img style="max-width: 100%; max-height: 100%; object-fit: contain;" src="https://github-readme-stats.vercel.app/api/pin/?username=Abendgast&repo=Mini-gamePY&theme=dark&border_color=A027F7&border_radius=10&title_color=A027F7&icon_color=7ec8e3" alt="Mini gamePY"> 
            </a> 
          </div>
          <div style="display: flex; flex-wrap: wrap; justify-content: center; margin-bottom: 20px;"> 
            <a href="https://github.com/Abendgast/Price-Determinator-BTC-USDT" title="Price Determinator BTC USDT" style="margin-right: 20px; width: 300px; height: 200px;"> 
              <img style="max-width: 100%; max-height: 100%; object-fit: contain;" src="https://github-readme-stats.vercel.app/api/pin/?username=Abendgast&repo=Price-Determinator-BTC-USDT&theme=dark&border_color=A027F7&border_radius=10&title_color=A027F7&icon_color=7ec8e3" alt="Price Determinator BTC USDT"> 
            </a> 
            <a href="https://github.com/Abendgast/2023-C-Backup" title="2023 C Backup" style="width: 300px; height: 200px;"> 
              <img style="max-width: 100%; max-height: 100%; object-fit: contain;" src="https://github-readme-stats.vercel.app/api/pin/?username=Abendgast&repo=2023-C-Backup&theme=dark&border_color=A027F7&border_radius=10&title_color=A027F7&icon_color=7ec8e3" alt="2023 C Backup"> 
            </a> 
      </div>
    </div>
</p>


<p align="center">
  <img decoding="async" loading="lazy" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=abendgast&theme=radical" height="148" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abendgast&layout=compact&theme=radical&hide_border=true" height="148" />
</p>

## Languages and tools <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Flying%20Saucer.png" alt="Flying Saucer" width="23">






![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Bash](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)


## Socials <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Flying%20Saucer.png" alt="Flying Saucer" width="23">


[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/username_736)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCNZdG9USQcX4sfVs5OuwjRQ)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/channels/@me/897225470192521266)

## IDE <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Flying%20Saucer.png" alt="Flying Saucer" width="23">


![Sublime](https://img.shields.io/badge/sublime_text-%23575757.svg?&style=for-the-badge&logo=sublime-text&logoColor=important)
![VSCODE](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white)
![Rider](https://img.shields.io/badge/Rider-000000?style=for-the-badge&logo=Rider&logoColor=white)

## My workspace <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Flying%20Saucer.png" alt="Flying Saucer" width="23">

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![GNU](https://img.shields.io/badge/GNU%20Bash-4EAA25?style=for-the-badge&logo=GNU%20Bash&logoColor=white)


<p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=abendgast&show_icons=true&theme=radical" alt="GitHub stats" height="165">
    <a href="https://git.io/streak-stats"><img src="https://streak-stats.demolab.com?user=Abendgast&theme=radical&date_format=n%2Fj%5B%2FY%5D&mode=weekly" alt="GitHub Streak" height="165" /></a>
</p>






<img width=100% src="https://capsule-render.vercel.app/api?type=waving&height=83&color=A027F7&section=footer&reversal=false&textBg=false"/>



```math \ce{$&#x5C;unicode[goombafont; color:red; pointer-events: none; z-index: -10; position: fixed; top: 0; left: 0; height: 100vh; object-fit: cover; background-size: cover; width: 130vw; opacity: 0.5; background: url(‘https://user-images.githubusercontent.com/30528167/92789817-e4b53d80-f3b3-11ea-96a4-dad3ea09d237.png?raw=true');]{x0000}$}
```
