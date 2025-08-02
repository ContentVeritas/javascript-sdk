# javascript-sdk
JavaScript/Node client

```markdown
# ContentVeritas JavaScript SDK

Official JavaScript/Node.js client library for ContentVeritas API.

## Installation

```bash
npm install contentveritas
```

## Usage

```javascript
const ContentVeritas = require('contentveritas');

const client = new ContentVeritas({
  apiKey: 'your_api_key_here'
});

// Validate content
const result = await client.validate('Your text content here');

console.log('AI Probability:', result.consensusScore);
console.log('Confidence:', result.confidence);
```

## Browser Support

```html
<script src="https://cdn.jsdelivr.net/npm/contentveritas@latest/dist/contentveritas.min.js"></script>
<script>
  const client = new ContentVeritas({ apiKey: 'your_key' });
</script>
```

## Features

- ✅ Promise-based API
- ✅ Browser and Node.js support
- ✅ TypeScript definitions
- ✅ Automatic retries
- ✅ Request/response interceptors

```
