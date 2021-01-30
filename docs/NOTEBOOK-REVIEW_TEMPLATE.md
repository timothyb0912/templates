# Notebook Review Guide


## Usefulness

This template is useful when reviewing Jupyter notebooks for:
- productionization as source code
- publishing as a notebook tutorial.


## Questions


### Requirements

What requirements does the notebook's code need to fulfill, exhaustively?

>


### API

How do I use the notebooks tools?  

>

What are the inputs and outputs of the notebook or its main function?

>


### Tests

Does the notebook's code have any tests?  

>

What in the notebook must be minimally changed to make it testable?

>


### Architecture

What is the architecture of the code in the notebook?  
Draw a diagram of it.  

>

Is this the best architecture I can think of, given project constraints?  
What would an ideal / better architecture look like?

>


### Risk management

Why would this notebook's code fail to deliver on its requirements?  

>

How does the notebook mitigate these risks?

>


### Red flags

Are there any immediate red flags or best practice violations?  

>

Are there any visible nitpicks?

>

Can the issues above be automatically fixed? Leave a note for yourself or others.

>


### Commits

Have the commits been rebased / squashed for clarity? 1 commit / branch.  

>

Does the commit title imperatively express the code change's content?  

>

Does the commit body express why the change's design rationale?  
(It should either state a rationale or link to a decision record.)

>


### Documentation

Does the notebook have:
- { module | class | function } docstrings?
  >

- type-hints?
  >

- comments?
  >


### Executability

Does the notebook run on your computer?  

>

Are all requirements captured in `requirements.in` or installed in the notebook?

>
