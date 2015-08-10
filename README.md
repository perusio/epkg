# epkg Package manager

## Introduction

This is the debianization of the `epkg` package manager.

epkg (pronounced like the letter 'E' and the word "package") is a fast
and flexible package management tool.  Here are some of its features:

 * Supports Encap package format versions 1.0, 1.1, 2.0, and 2.1.
 * Can manage multiple versions of the same package, so you can upgrade
   without removing files.
 * Provides both batch and single-package modes.
 * Automatically extracts tar archives for easy package installation.
 * Logs package installation and removal.
 * Optional support for retrieving packages via FTP or HTTP for one-step
    package installation.
 * Optional support for package profile format to automate package
   creation.

## Installation

 1. Clone the repository:
    
        git clone git@github.com:perusio/epkg.git

 2. In the package directory do:
    
        git-buildpackage
       
 3. Done.
