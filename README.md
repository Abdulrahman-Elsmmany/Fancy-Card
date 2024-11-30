# Fancy Counter

A sleek, interactive counter application built with React. Features a modern UI with increment/decrement controls, keyboard shortcuts, and a premium tier limit.

## Features

- Increment/decrement counter values (0-5 range)
- Spacebar shortcut for quick increments
- Premium tier teaser at maximum value
- Responsive design for all screen sizes
- Modern gradient background
- Smooth animations and transitions

## Tech Stack

- React
- Radix UI Icons
- CSS3 with modern features (Grid, Flexbox, CSS Variables)
- Google Fonts (Inter)

## Installation

```bash
# Clone repository
git clone [repository-url]

# Install dependencies
npm install

# Start development server
npm run dev
```

## Usage

- Click `+` to increment
- Click `-` to decrement
- Press `Spacebar` to increment
- Click reset icon to clear counter
- Counter locks at 5 (Premium tier feature)

## Component Structure

```
App
└── Card
    ├── Title
    ├── Count
    ├── Reset
    └── ButtonContainer
        ├── CountButton (minus)
        └── CountButton (plus)
```

## Contributing

1. Fork repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open pull request

## License

MIT
