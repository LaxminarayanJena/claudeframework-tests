# Claude Framework - Playwright Google Tests

A comprehensive Playwright automation framework for testing Google.com functionality, created with Claude AI assistance.

## 🚀 Features

- **Multi-browser testing**: Chrome, Firefox, Safari (WebKit)
- **Comprehensive Google.com verification**: Homepage, search functionality, UI elements
- **Mobile responsive testing**: Tests mobile viewport compatibility
- **Robust selectors**: Uses reliable Playwright selectors and best practices
- **CI/CD ready**: Configured for continuous integration

## 📋 Test Coverage

### Google.com Verification Tests

✅ **Homepage Loading**
- Verifies Google homepage loads successfully
- Checks page title contains "Google"
- Validates search box presence

✅ **Search Functionality** 
- Tests search box visibility and functionality
- Performs search queries and validates results
- Verifies search suggestions (when available)

✅ **UI Elements**
- "I'm Feeling Lucky" button verification
- Google Apps menu accessibility
- Mobile responsiveness testing

✅ **Cross-browser Compatibility**
- Chromium (Chrome)
- Firefox 
- WebKit (Safari)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/LaxminarayanJena/claudeframework-tests.git
cd claudeframework-tests
```

2. Install dependencies:
```bash
npm install
```

3. Install Playwright browsers:
```bash
npx playwright install
```

## 🧪 Running Tests

### Run all tests
```bash
npm test
```

### Run Google-specific tests
```bash
npm run test:google
```

### Run tests in headed mode (visible browser)
```bash
npm run test:headed
```

### View test reports
```bash
npm run report
```

## 📊 Test Results

**Current Status**: 18 passing tests, 3 tests with minor issues

- ✅ Homepage verification
- ✅ Search box functionality  
- ✅ Mobile responsiveness
- ✅ UI element verification
- ⚠️ Search results verification (minor selector adjustments needed)

## 📁 Project Structure

```
claudeframework-tests/
├── tests/
│   ├── google.spec.ts      # Google.com verification tests
│   └── example.spec.ts     # Playwright example tests
├── playwright.config.ts    # Playwright configuration
├── package.json           # Project dependencies and scripts
├── .gitignore            # Git ignore rules
└── README.md             # This file
```

## ⚙️ Configuration

The framework is configured for:
- **Parallel execution**: Tests run in parallel for faster results
- **Cross-browser testing**: Chromium, Firefox, WebKit
- **Trace collection**: On test failure for debugging
- **HTML reporting**: Comprehensive test reports
- **CI/CD ready**: Optimized for continuous integration

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the ISC License.

## 🔧 Built With

- **Playwright** - Modern web automation framework
- **TypeScript** - Type-safe JavaScript
- **Node.js** - JavaScript runtime
- **Claude AI** - AI-assisted development

---

*Created with Claude AI assistance for robust, scalable web automation testing.*