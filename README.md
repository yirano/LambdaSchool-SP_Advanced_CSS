## Self-Study Questions

**1. What is the difference between an adaptive website and a fully responsive website?**

An adaptive website are styled using media queries, where different versions are styled for different screen sizes. The user experience on this, in my opinion, are superior because adaptive websites are optimized for each device/screen sizes.

Responsive designs is just one version that adjusts itself based on the user's screen size. 

**2. Describe what it means to be mobile first vs desktop first.**

Mobile first are designs that are styled from the smallest screen sizes to larger, whereas the desktop is the other way around.

**3. What does `font-size: 62.5%` in the `html` tag do for us when using `rem` units?**

A font-size that is 62.5% is about 10px. This would convert, or translate, every rem unit as 10px, meaning 1rem = 10px and 2rem = 20px.

**4. How would you describe preprocessing to someone new to CSS?**

Preprocessing is a tool that allows for faster CSS styling with benefits such as initializing a font-family to a certain variable. For example, instead of having to repeat "font-family: 'Arial', sans-serif" for every element that uses that font, you can put that into a variable such as @bodyText. You can also initialize variables for colors so that you won't have to memorize the hexcode, or even use functions (amongst others) to keep your code looking DRY.

**5. What is your favorite concept in preprocessing? What is the concept that gives you the most trouble?**

I LOVE that I can use variables to remember my colors. Instead of trying to memorize or keep notes of my hexcodes of every color being used, I can just call @yellow, or @headerColor. 

