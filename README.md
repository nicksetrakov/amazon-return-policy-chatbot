# Amazon Return Policy Chatbot

This is a basic AI chatbot that answers questions related to Amazon's Return Policy. The chatbot was created using Voiceflow and is embedded on a web page.

## Installation

To add the chatbot to your website, include the following code snippet before the closing `</body>` tag on all pages where you want the widget to appear:

```html
<script type="text/javascript">
  (function(d, t) {
      var v = d.createElement(t), s = d.getElementsByTagName(t)[0];
      v.onload = function() {
        window.voiceflow.chat.load({
          verify: { projectID: '66b4c752fdb3fb66c6fa328d' },
          url: 'https://general-runtime.voiceflow.com',
          versionID: 'production'
        });
      }
      v.src = "https://cdn.voiceflow.com/widget/bundle.mjs"; v.type = "text/javascript"; s.parentNode.insertBefore(v, s);
  })(document, 'script');
</script>
```

To install and run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/nicksetrakov/amazon-return-policy-chatbot.git
   ```
2. Open index.html in your web browser to interact with the chatbot.

## Features
- Answers questions about Amazon's return policy.
- Redirects non-return related queries to customer support.
## Technologies Used
- Voiceflow: For chatbot creation and management.
- JavaScript: For integrating the chatbot on a webpage.

## Live Demo
You can view the chatbot in action here.

https://nicksetrakov.github.io/amazon-return-policy-chatbot/
