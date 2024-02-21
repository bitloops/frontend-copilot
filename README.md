# Bitloops Frontend Copilot
Bitloops is an AI-Powered Front-End Companion in VS Code that transforms your design into high-quality, maintainable code effortlessly.

Before building Bitloops we tried out a lot of products out there that claimed to convert our Figma designs into code. Nonetheless, they required the designs to be constructed in a very specfic way basically asking the designers to think like developers. We know very well that most designers are not interested in that and won't be changing their habits any time soon. Bitloops is the only tool that generates useful code for professional developers. It doesn't need a perfect design to work but rather it tries to generate very decent code while still preserving the design intention. Our goal is not to generate a pixel perfect version of the design nor to generate 100% of the code. Rather we are aiming on correctly generating a big chunk of the work a frontend developer needs to do requiring further work but **minimizing** any rework. 

The following are some of the things we are working very hard towards:

- Priority on TypeScript vs JavaScript (we love types!)
- Priority on TailwindCSS (it just makes sense!)
- Generating most of your presentational components
- Exporting all your images automatically
- Generating your design system and then your theme automatically (even if they are not yet images on the design (e.g. vectors)
- Generating StoryBook stories for all your presentational components
- No hardcoded texts in React code and texts passed via props in order to be able to do translations etc.

Our open alpha is completely free! A lot that we want to build are still missing but it will be getting better by the day.

## Getting Started

1. Open Your Design
Launch Figma and open the design file you want to convert

<img width="158" alt="image" src="https://github.com/bitloops/frontend-copilot/assets/1571105/c3da0d8e-aaa7-4f6a-b2eb-b901d1fac044">

2. Invite Artie
Share your design with Artie, a dedicated Frontend AI assistant, by adding ai@bitloops.com as a viewer.

![invite-artie](https://github.com/bitloops/frontend-copilot/assets/1571105/978bfb70-ecca-4f80-89fb-eada1a14d916)

3. Tag Artie
Add a comment anywhere on the design tagging Artie and typing:“Hey @Artie, convert this design into code, please.

![tag-artie](https://github.com/bitloops/frontend-copilot/assets/1571105/e39b11a6-adea-4b35-9363-53fb072cd054)

4. Retrieve your code
Artie will process your request and provide instructions on how you can access and integrate the generated code into your VS Code project seamlessly.

![image](https://github.com/bitloops/frontend-copilot/assets/1571105/0b64903d-c437-4c87-92be-d903770b44c5)

## Where we're at

- Detecting and organising your content based on page sections
- Exporting most of your images automatically
- Exporting HTML and TailwindCSS (HTML can be more easily converted into any framework manually and is a good foundation before we launch React)
- Generating a partial theme

In our closed alpha we are also:
- Generating React and Next.js code
- Generating React components
- Generating StoryBook stories
- Naming and understanding things things even better using more AI

If you want to join our closed alpha please reach out on our [Discord](https://discord.gg/vj8EdZx8gK) 

## What we need from you

- FEEDBACK: Please create issues and reach out with any comments or questions
- More feedback
- Try it out! Call Artie and install our VS Code Extension to get started
- If you like any of what you see or read maybe star us
- And above all (but not above feedback) spread the love!
