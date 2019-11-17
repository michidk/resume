# Resume
My personal resume.

## Prerequisites
Dependencies are Texlive-Full and make.
I am using [this Docker-image](https://github.com/michidk/texlive-docker) to build the pdf.

## Building
To build the .pdf-file, execute:
```make pdf```

## Development
To launch latexmk in development-mode with live reloading, use:
```make watch```

## Commands
Additional commands are available:

To clean the output folder from built artifacts:
```make clean```

To remove the whole output folder:
```make purge```
