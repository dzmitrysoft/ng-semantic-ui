Semantic UI Angular Integrations, written in pure Angular - **no JQuery required**.

## Introduction

```bash
npm install --save @piratuks/ng-semantic-ui
```
https://www.npmjs.com/package/@piratuks/ng-semantic-ui 
<br />

Angular and jQuery don't go together - this is the fundamental principal of this library. It provides Angular component versions of the Semantic UI modules, so that you don't need to add jQuery to your app.

Note that only Semantic UI elements that use jQuery are recreated here - those written purely in CSS aren't included as they can be used in Angular apps already.

## Installation & Usage

See the [Documentation](https://github.com/piratuks/ng-semantic-ui/tree/master/demo) for installation instructions and extensive examples.

## Dependencies

- [Angular](https://angular.io) (^8.0.0)
- [Semantic UI CSS](http://semantic-ui.com/) (^2.3.1) (jQuery is **not** required)

## Component Support

| Icon                    | Description                                                                         |
| ----------------------- | ----------------------------------------------------------------------------------- |
| :white_check_mark:      | Component supported by ng55semanticui.                                              |
| :rocket:                | Semantic UI plugin supported by ng55semanticui (not in Semantic UI Core).           |
| :ballot_box_with_check: | Component supported natively by [Semantic UI](https://semantic-ui.com/) (CSS only). |
| :x:                     | Component currently unavailable.                                                    |
| :no_entry_sign:         | Component not applicable to Angular.                                                |

| Elements                          | Collections                        | Views                                | Modules                       | Behaviors                       |
| --------------------------------- | ---------------------------------- | ------------------------------------ | ----------------------------- | ------------------------------- |
| :ballot_box_with_check: Button    | :ballot_box_with_check: Breadcrumb | :ballot_box_with_check: Advertisment | :white_check_mark: Accordion  | :no_entry_sign: API             |
| :ballot_box_with_check: Container | :ballot_box_with_check: Form       | :ballot_box_with_check: Card         | :white_check_mark: Checkbox   | :no_entry_sign: Form Validation |
| :ballot_box_with_check: Divider   | :ballot_box_with_check: Grid       | :ballot_box_with_check: Comment      | :rocket: Collapse             | :rocket: Localization           |
| :ballot_box_with_check: Flag      | :ballot_box_with_check: Menu       | :ballot_box_with_check: Feed         | :rocket: Datepicker           | :x: Visibiltiy                  |
| :ballot_box_with_check: Header    | :white_check_mark: Message         | :ballot_box_with_check: Item         | :white_check_mark: Dimmer     |                                 |
| :ballot_box_with_check: Icon      | :rocket: Pagination                | :ballot_box_with_check: Statistic    | :white_check_mark: Dropdown   |                                 |
| :ballot_box_with_check: Image     | :ballot_box_with_check: Table      |                                      | :x: Embed                     |                                 |
| :ballot_box_with_check: Input     |                                    |                                      | :white_check_mark: Modal      |                                 |
| :ballot_box_with_check: Label     |                                    |                                      | :white_check_mark: Popup      |                                 |
| :ballot_box_with_check: List      |                                    |                                      | :white_check_mark: Progress   |                                 |
| :ballot_box_with_check: Loader    |                                    |                                      | :white_check_mark: Rating     |                                 |
| :ballot_box_with_check: Rail      |                                    |                                      | :white_check_mark: Search     |                                 |
| :ballot_box_with_check: Reveal    |                                    |                                      | :x: Shape                     |                                 |
| :ballot_box_with_check: Segment   |                                    |                                      | :white_check_mark: Sidebar    |                                 |
| :ballot_box_with_check: Step      |                                    |                                      | :x: Sticky                    |                                 |
|                                   |                                    |                                      | :white_check_mark: Tab        |                                 |
|                                   |                                    |                                      | :white_check_mark: Transition |                                 |

## Credits

Essentially this is forked version of https://github.com/edcarroll/ng2-semantic-ui. Main improvements are:

- updated project and project dependencies to be compatible with angular 8
- translation module implementation changes
