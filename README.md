# `tilde` - A tilde-launcher proposal in Python

This is my proposal for the tilde town program launcher. Here are the features that make it compliant with the specs:

 - It has a help menu that, while not meeting the format of the specs, gives an example usage string and description.
 - It implements the contrib system beautifully (IMO)

Here are the things I have left to make before this proposal can be considered a true answer to the specs:

 - [ ] Implement submit process
 - [ ] Implement other commands shown in help example (see below)
 - [ ] Polish some rough logic

## Top-level commands

 - [X] help - complete
 - [X] contrib - complete
 - [X] chat - complete
 - [ ] mail - just need to write this one
 - [ ] submit - See Questions below

## Questions

### `tilde submit`

 - How should this be accomplished?
 - Is this supposed to be only for ben or for an admin in general to help?
 - If the answer to the previous question is the latter, how should this be accomplished?

## Requirements

In `/tilde/special`, put:

 - `list` - see list program in this directory
