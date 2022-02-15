# Overview

Working through introductory docker tutorial here https://www.youtube.com/watch?v=pTFZFxd4hOI 

For notes, see https://docs.google.com/document/d/1XMLwVzXHhY640Y5SaCsMXgDFiv4o1XBIUHyssBLQII4/edit?usp=sharing (private link)  

## Notes

On current mac, with Apple M1 chip, always create image from dockerfile while specifying the platform, eg:
- docker build -t blueluke/practice:hello-docker . --platform linux/amd64