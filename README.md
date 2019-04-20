# Project Ideas API
A static API for serving project ideas JSON to my project tracker.

## Data Structure
```js
{
  "currentList": "listOne",
  "projectLists": [
    {
      "listName": "listOne",
      "source": "urlOne"
      "projects": [
        {
          "text": "Make a party game that allows users to take turns playing mini-games",
          "category": "interactivity",
          "completed": false,
        },
        ...
      ]
    },
    {
      "listName": "listTwo",
      "source": "urlTwo",
      "projects": [
        {
          "text": "Write a workout app that stores user workouts to a database.",
          "category": "database",
          "completed": false,
        },
        ...
      ]
    },
    ...
  ]
}
```