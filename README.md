# Data Visualization and Analysis Software

Powerfull data analysis and visualization tool writte in pure Java. Can be included in the application.
Twig library is evolution of groot, which was initially developped for small data visualization while developing data reconstruction codes,
and since became very improtant part of CLAS12 online and offline software.This project is actively developped.


It is designed as a **learning project for data visualization and scientific plotting in Java**.

---

# Features

* Histogram visualization
* Graph plotting (X-Y plots)
* Random data simulation
* Interactive canvas window
* Scientific data visualization
* Built using Maven and Java

---

# Tech Stack

* **Java**
* **Maven**
* **GROOT Visualization Library**
* **VS Code**
* **Git & GitHub**

---

# 📂 Project Structure

```
groot-project
│
├── src
│   └── main
│       └── java
│           └── App.java
│
├── tutorials
│   └── demo examples
│
├── images
│   └── screenshots
│
├── pom.xml
└── README.md
```

---
<img src="https://github.com/Akashchandai/Data-Visualization-using-GROOT/blob/dd27476418115a2a0e9c83a3c0c7e66f7df4eb5b/images/twig%20image.png">
#Installation

# 📊 Example Code

```java
import org.jlab.groot.data.H1F;
import org.jlab.groot.ui.TCanvas;

public class App {

    public static void main(String[] args) {

        H1F histogram = new H1F("Histogram",100,-5,5);

        for(int i=0;i<10000;i++){
            histogram.fill(Math.random());
        }

        TCanvas canvas = new TCanvas("Canvas",800,600);
        canvas.draw(histogram);
    }
}
```

This program generates a **histogram visualization window**.

---

# Gallery


<table class="center" width="100%">
    <tr>
        <td width="50%">
            <figure>
                <a href="https://github.com/gavalian/twig/blob/main/tutorials/plotting/advanced_graph_fitting.java">
                 <img src="https://github.com/gavalian/twig/blob/main/tutorials/images/figure_advanced_graph_fitting.png" alt=""></a>
                <figcaption><h2></h2></figcaption>
            </figure>
        </td>
        <td width="50%">
             <a href="https://github.com/gavalian/twig/blob/main/tutorials/plotting/advanced_bar_chart.java">
              <img src="https://github.com/gavalian/twig/blob/main/tutorials/images/figure_advanced_bar_chart.png" alt=""></a>
                <figcaption><h2></h2></figcaption>
        </td>
    </tr>   
 <tr>       
   <td width="50%">
            <figure>
                <a href="https://github.com/gavalian/twig/blob/main/tutorials/plotting/confusion_matrix.java">
                 <img src="https://github.com/gavalian/twig/blob/main/tutorials/images/figure_confusion_matrix.png" alt=""></a>
                <figcaption><h2></h2></figcaption>
            </figure>
        </td>
        <td width="50%">
             <a href="https://github.com/gavalian/twig/blob/main/tutorials/images/figure_slice_graph_3d.png">
              <img src="https://github.com/gavalian/twig/blob/main/tutorials/images/figure_slice_graph_3d.png" alt=""></a>
                <figcaption><h2></h2></figcaption>
        </td>
    </tr>
</table>

---

# Learning Purpose

This project helps developers understand:

* Java-based data visualization
* Scientific plotting
* Histogram and graph generation
* Using external libraries with Maven

---

# Future Improvements

* CSV dataset visualization
* Multiple graph dashboards
* Interactive UI
* Data analytics integration

---

# Author

**Akash Chandai**

* GitHub: https://github.com/Akashchandai
* LinkedIn: https://linkedin.com/in/akash-chandai

---

⭐ If you like this project, consider giving it a **star on GitHub**!

```
paste - - < epip_hb.txt > epip_hb_joined.txt
```

