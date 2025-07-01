### **Decoding I-94 Traffic: What Causes the Jams? 🚗💨**

We've all been stuck in traffic, but what really causes it? This project dives into a dataset from the I-94 interstate to figure out the key indicators of heavy traffic. Is it the time of day, the weather, or something else? Let's find out!

#### **Our Investigation 🗺️**

1.  **Day vs. Night ☀️🌙:** We started by splitting the data into daytime and nighttime hours. It quickly became clear that the real action happens during the day, so we focused our analysis there.

2.  **Time is Everything ⏰:** We looked at how traffic volume changes over different time periods:
    *   **By Month:** Traffic is heaviest in the spring and fall.
    *   **By Day of the Week:** Weekdays are much busier than weekends, with traffic peaking mid-week.
    *   **By Time of Day:** The morning and evening commutes are the busiest times on weekdays.

3.  **What About the Weather? 🌦️:** We also looked at how weather affects traffic. While most weather conditions don't have a huge impact, we did find that **light rain and snow** can lead to more congestion.

#### **The Verdict ⚖️**

The biggest indicators of heavy traffic on the I-94 are **time-based**. The morning and evening commutes on weekdays, especially during the spring and fall, are the busiest times. While weather can play a role, it's not as significant as the time of day.

#### **Tech We Used 🛠️**

*   Python
*   Pandas & NumPy
*   Matplotlib & Seaborn
*   Jupyter Notebook

#### **See for Yourself! 🚀**

Want to dig into the data and see our analysis?

1.  **Clone the repo:**
    ```bash
    git clone https://github.com/jackren0000/Finding-Heavy-Traffic-Indicators-on-I-94.git
    ```
2.  **Install the libraries:**
    ```bash
    pip install pandas numpy matplotlib seaborn jupyter
    ```
3.  **Run the notebook:**
    ```bash
    jupyter notebook main.ipynb
    ```