# Simple Interactive Games For Toddlers

Intuitive, interactive Games For Toddlers to play on touch screen

## Game list
| Name | Game Play | Age level |
|-------|----------|------------|
|[Burst Balloons](https://arun-ks.github.io/ToddlerGames/BurstBaloons.html) | Pop Balls falling from top of the screen | 1.5 years+ | 
|[Sort Alphabet](https://arun-ks.github.io/ToddlerGames/SortAlphabets.html) | Click on alphabet in correct sequence  | 3 years+ |
|TBD | Hold screen for few seconds  | 4 years+ |


## Installation
These use single page HTML files along with some small mp3s. You can use the online version [here](https://arun-ks.github.io/ToddlerGames/).

## Co-Development with ChatGPT
Most of the games were created with ChatGPT. The quick prototyping allowed revision & refinement of requirements.

The final code was created after many back-and-forth as the generated code had to be troubleshooted. I had to suggest corrections & improvements in the code till we got to the final forms.

### Prompt to get Prompt
Once the final code is generated, the following prompt was used to generate prompt for the thread.

> Please give me a full chatGPT prompt which would have generated the last HTML .
> The prompt should be detailed so that if some other use sends the same prompt, an almost identical html file would be generated.

<details closed>
<summary>ChatGPT prompt to generate [Burst Balloons Game](BurstBaloons.html)  </summary>

> Create an HTML webpage with an interactive animation. The animation should involve colorful blobs falling from the top of the screen to the bottom. When a blob reaches the bottom, it should pop or explode with a sound effect. Users should also be able to click or touch a blob to make it pop instantly with a sound effect.
> Here are the specific requirements:
> 1. The webpage should have a container element that covers the entire viewport, ensuring no overflow.
> 2. Blobs should be created and fall from the top of the screen to the bottom.
> 3. Blobs should have a circular shape (border-radius: 50%) and should be of random sizes, with a minimum size of 50px.
> 4. Blobs should have random colors. You can use a function to generate random colors.
> 5. Blobs should fall at a speed determined by a user-controllable slider. There should be a slider control that allows users to adjust the falling speed of the blobs.
> 6. Users should be able to click or touch a blob to make it pop. When a blob is clicked or touched, it should pop with an animation and play a pop sound effect. The pop sound effect should be randomly selected from a list of three sound files: "pop0.mp3," "pop1.mp3," and "pop2.mp3."
> 7. The first five blobs should be created within a gap of 0.05 seconds from page load. After that, blobs should be continuously generated at a fixed interval of 0.4 seconds.
> 8. The animation for the falling blobs should be smooth and include easing. Blobs should scale slightly as they fall but should maintain their original shape and color throughout the animation.
> 9. Ensure that the animation is visually appealing and that the blobs smoothly disappear after popping.
> 10. Use appropriate HTML, CSS, and JavaScript to implement this animation. Make sure to include any necessary event listeners and handlers.
> 
> Please provide a complete HTML file that includes all the necessary code, styles, and scripts to achieve the described animation. Ensure that the pop sound files are included and properly referenced. If any additional assets or files are required, specify how they should be organized within the project folder.

</details>
