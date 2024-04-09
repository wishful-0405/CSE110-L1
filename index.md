#Lab 1 User Page
**For Austin Yeung**
*Due ~~4/9~~ 4/10 *

> Why are you creating another markdown page
A quote from a friend watching me work

The coding stuff:
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