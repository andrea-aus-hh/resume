FROM texlive/texlive:latest
RUN apt-get update && apt-get install -y \
    texlive-fonts-recommended \
    texlive-latex-extra \
    texlive-fonts-extra \
    biber \
    && rm -rf /var/lib/apt/lists/*
WORKDIR /workspace

ENTRYPOINT ["pdflatex"]
