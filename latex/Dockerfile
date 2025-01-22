FROM texlive/texlive:small

RUN apt-get update && apt-get install -y \
    texlive-latex-base \
    texlive-latex-extra \
    texlive-fonts-recommended \
    texlive-fonts-extra \
    biber \
    && rm -rf /var/lib/apt/lists/*