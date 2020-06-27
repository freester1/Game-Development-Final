## NEU Game Development
2D Adventure RPG developed for Northeastern's Game Development program. Features a novel text-based narrative centered around self-discovery.

Eric Crawford put together a great write up on this project! Check it out here:

https://ercraw.com/talking-time

## Team Members
Thank you to everyone who has contributed, both on the team and in class!

Arvin Sharma - Project, Code lead

Eric Crawford - Art, Design lead

Caroline Pasyanos - Design support

Michael Lucas - Code support

Arjun Arora - Audio tech

Lena Wyant - Narrative support

### Technical Details
Project for gamedev. All object classes will be put in the root dir, hopefully it won't get too crowded.

- images in data/
- maps in maps/

useful stuff to have in your ~/.bash_profile or equiv.
```
## Create love binary by doing `clv binary_name`
clv () {
   zip -9 -r $1.love .
}

## Run love binary by typing `lv binary_name`
lv () {
  love $1.love
}

## Compile and run by typing `clvl binary_name`
clvl () {
  clv $1 && lv $1
}

## Delete love binaries
rml () {
  rm *.love
}
```
