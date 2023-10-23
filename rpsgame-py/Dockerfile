FROM python:alpine

LABEL version="01.01.01"

WORKDIR /the/workdir/path

COPY RockPaperScissorsGame.py /the/workdir/path/

RUN mv RockPaperScissorsGame.py rockpaperscissorsgame.py

CMD ["python", "rockpaperscissorsgame.py"]