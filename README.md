# DailyEmailDigest
Código en python capaz de enviar un correo diario a personas que estén subscritas en donde puedan ver información importante respecto al clima, noticias, etc.

### Autor: Barron Stone.

Diego Valenzuela lo replica en seguimiento al curso "Python projects" creado por Barron Stone en la plataforma Linkedin Learning.

### User stories
As a digest recipent (who), I want to receive an email every morning with current and useful information (the goal/what) so that I know what is going on in the world and learn something new everyday (why).

### Use Case
- Title: Read Tweets about a Twitter Trend (what the goal is).
- Actor: The digest recipent (who desires it).
- Scenario (how is it accomplished):
  - The recipent opens the digest email in the email client.
  - The recipent sees an interesting Twitter trend.
  - The recipient clicks on the trend link.
  - The link opens a web browser to a page of related tweets.
  
### Requirements: 
  - Generate a random inspirational quote.
  - Retrieve current weather forecast for specified location.
  - Retrieve current Twitter trends.
  - Retrieve a random Wikipedia article.
  - Formar content into a email.
  - Send email to specified recipients.

Nouns: quote, forecast, location, trends, article, content, email, recipients (potential objects in my program).

Verb Phrases: generate quote, retrieve forecast, retrieve trends, retrieve article, format content, send email, configure content, add recipients, remove recipients, schedule time, configure credentials.

Objects and their actions:
  - Content: Generate quote, retrieve forecast, retrieve trends, retrieve article.
  - Email: format content, send email.
  - GUI: configure content, add recipients, remove recipients, schedule time, configure credentials.

### Non-functionals requirements (how should it do it):
- Configurable using admin GUI.
- Extensible to add more content types.
- Resilient to content errors.

### The aplicattion must enable the admin to:
- Configure wich content sources to include in email.
- Add recipients.
- Remove recipients.
- Schedule recurring daily time to send email.
- Configure sender credentials.
  
