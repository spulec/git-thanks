# Git Thanks

A way to thank the owner of a github repository

## Installation

Configure bin/git-thanks with your email server information and change the default message.

    sudo python setup.py install
    

## Usage

Run these inside a git working directory.

This will send an email with the default message.

    git-thanks 

This will send a custom message
    
    git-thanks -m "Custom message here"
