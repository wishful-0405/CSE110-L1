#Lab 1 User Page

**For Austin Yeung**
*Picture of me*
![Meeeeeeeeeee](tyomateee2-1582705988482011137-20221019_051127-img1.png)

*Due ~~4/9~~ 4/10*

> Why are you creating another markdown page
> 
A quote from a friend watching me work


Basic Table of Contents
[Code](##the-coding-stuff:)
[About me](##and-the-about-me-section:)


##The coding stuff:

I know: java, html, js, c, c++, and yannow more.
    proof I know java
    ```
    class Text extends JPanel {
        
        public void load() {
        try {
            
        String taskString;
        Vector<String> listings = new Vector<String>();
        FileReader fileR = new FileReader("tasks.txt");
        BufferedReader bufferR = new BufferedReader(fileR);
        
        while (bufferR.ready()) {
            taskString = bufferR.readLine();
                listings.add(taskString);
        }

            bufferR.close();

            JList listMain = new JList(listings);
            this.add(listMain);
            revalidate();

        }
        catch (IOException exception) {
        System.out.println("loadTasks() not implemented");
        }

        }
    }
    ```

##And the About me section:

Hi I'm another student in CSE 110 SP24. People call me Austin and I'm a computer engineering major in my senior yr. But enough of the academics stuff, here's some random facts about me.


[My favorite site](https://thisfoxmeows.com/)

In no particular order, my favorite foods:
- Mac n Cheese
- Ramen
- Milk Tea

And in order, my favorite video games:
1. Halo
2. Stardew Valley
3. KSP

My todo for this page
- [x] Markdown formats
- [x] Images


[Lookatthispokemon](701e2cf4b46daa41e9d91d892_e8f146aa_540.png)