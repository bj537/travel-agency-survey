# Travel Agency Survey System

A web-based survey system for travel agencies to collect and analyze feedback about their operations and Excel automation usage.

## Features

- Interactive survey form
- Response data visualization
- Real-time data storage
- Responsive design
- Dark mode support
- Data export capabilities

## Project Structure

```
travel-agency-survey/
├── public/
│   ├── index.html          # Main survey form
│   └── saved-surveys.html  # Survey response viewer and analytics
├── .gitignore
└── README.md
```

## Pages

1. `public/index.html` - Main survey form
2. `public/saved-surveys.html` - Survey response viewer and analytics

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Chart.js for data visualization
- LocalStorage for data persistence

## Setup

1. Clone the repository
2. Open `public/index.html` in a web browser
3. Start collecting survey responses

## Data Storage

Survey responses are stored in the browser's localStorage. To export data:
1. Navigate to the saved surveys page
2. Use the browser's developer tools to access localStorage
3. Export the 'surveyResponses' data

## Contributing

Feel free to submit issues and enhancement requests! 