What can we write?

- Write some things about architecture style
- Why need API documentation a software (the particular software should be able
  to help volunteers to make their own client, etc)
- Describe domain semantics (form apiary):
  What is the thing you’re describing? Is it a chair or a bench? At first sight,
  it may feel obvious or even trivial to define the semantics of your
  application domain. However, make sure you list all the terms used in your
  application and get everybody on the same page of what they mean.
- Possible ways to go: swagger and apiary
  Why we choose apiary: has hosting, is easily trackable by git repo, nice
  layout, mock server.
  swagger: has all that but not the hosting part (?), *less documentation*, best
  thing the code generator, but we probably won't need one.