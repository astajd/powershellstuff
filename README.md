# Powershellstuff

Windows Powershell scripting

## What this repo contains
This repository contains simple powershell scripts. Some useful some less useful. Most of them were written while at work to help with my daily tasks.

## Zipfiles
Compress files lying around in a folder to a single folder. Use the variables to specify specific files to compress or, say define a filetype inside a folder eg. "*.txt"

## checkFileExistance
Run through array of files twice with a wait to see if there's a delay in a prior job that creates files. Used with Informatica prior to a data loading phase to see if files exist. Throws an error and logs which file was missing.

## Searchthrough
I wrote searchthough.ps1 based off an old script I found. A nice use case for the script would be filtering through log files for error messages. The script writes out all lines containing a user specified keyword from all the files in a folder that the user can also specify e.g searching all 'log' files for the keyword 'error'.

## Wordtotext
Searches through a specified folder, reads the content of word-files and converts them to .txt-files. Used this in combination with the searchthrough tool to run through multiple word-files and search for a few key words quickly

## Create-password
By running this the user can create a completely random password with their own computer, with no need to rely on creativity or untrustworthy websites to create said password.

## Openportest
This one sends a simple TCP-request to a specified port in a specified location to check if the server responds to tcp-requests. A successful run responds with no response and an unsuccessful one respons with a powershell error message.

## Powershell mailing tool
Used to send run failure messages from powershell scripts to notify users of the run failure.
