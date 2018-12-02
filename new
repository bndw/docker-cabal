#!/bin/bash
sudo docker build -t cabal .
sudo docker run -it --rm -p 3282 -v ${PWD}/.cabal:/root/.cabal cabal cabal --new

