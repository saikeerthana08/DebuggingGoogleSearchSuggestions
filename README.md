In this project, I fixed the **Google Search Suggestions** app by applying the concepts we have learned till now.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/google-search-suggestions-output.gif" alt="debugging google search suggestions" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Complete Instructions

<details>
<summary>Functionalities fixed</summary>
<br/>

Fixed the given code to have the following functionality

- Initially, all suggestions in the `suggestionsList` is displayed
- When a value is provided in the search input, then display the suggestions which include the search input irrespective of the case
- When the arrow of a suggestion is clicked, then the value of the search input is updated with the respective suggestion clicked
- The `GoogleSuggestions` component receives the `suggestionsList` as a prop. It consists of a list of suggestion objects with the following properties in each suggestion object

  |    Key     | Data Type |
  | :--------: | :-------: |
  |     id     |  Number   |
  | suggestion |  String   |

</details>
