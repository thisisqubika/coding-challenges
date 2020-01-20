## Intent

The intent of this challenge is to get a sense of how do you solve certain architectural and design problems, and how well do you document and test your work.

## The Challenge

Design an implement a subset of a React UI library. The library should also support themes and provide a default one, allowing the clients to write their own custom themes and to override existing ones. 

Also, as part of this challenge, you should build a demo application showcasing each component’s features, sample code and usage documentation.

### Components to design and implement

- Button
- Input Text
- Input Number 
  - _Allows only numbers, and formats them_
- Select Input 
  - _It should allow single and multiple selection_
- Autocomplete
  - _It should work independently of the data source (being a REST api, or an IndexedDB for example)_

Each component should have a set of unit tests covering each feature / behavior.

The demo app should have a `README` describing how to install its dependencies, build, and run.

Use `redux` as state manager for the demo app and `react-router` for page routing.

## Real World Examples for Inspiration

- [Ant Design](https://ant.design/docs/react/introduce)
- [Material UI](https://material-ui.com/)

## Deliverables

Both the UI library and the demo app must be published on GitHub. 

After completing the challenge, send an email to coding-challenge@moove-it.com including the GitHub’s repository url. Tag the version you want to deliver as `1.0.0`. 
