# Class 13

## Local Storage and How To Use It On Websites

### Answers

1. Why would a developer use local storage for a web application?

   - If they do not want to use server-side storage, as it is easier and more coste-effective.
 
2. What information should not be stored in local storage?

   - Sensitive information, such as Personally Identifiable Information (PII), authentication tokens, user locations and API keys.

3. Local storage can store what type of data? How would you convert it to that type before storing?

   - It can only store strings when they are in the same key, so there are issues with objects. The ways around this are to use the JSON.stringify() and JSON.parse() methods.
