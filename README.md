# Sparklight

Simple Lighthouse ETH 2.0 Validator ansible setup script. 

## Description

This is an attempt at an automted setup of a ETH 2.0 validator. So why use an install from scratch rather than a dockerized configuration? The answer is to only use this approach when testing mutiple hardware platforms.

## Usage

This configuration was designed for Ubuntu bionic 20.04 LTS

Log into your environment and install ansible

$ sudo apt-get install ansible

$ git clone https://github.com/NakamotoNetwork/Sparklight.git

$ cd Sparklight

$ ansiple

## Base Ubuntu

The base Ubuntu playbook is essentially the same except only basic tools such as tmux, curl, go and build-essentail is installed.
