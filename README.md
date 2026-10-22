# Cryptococcosis Risk Score in Kidney Transplant Recipients

Static clinical web application designed for the risk stratification of cryptococcosis in kidney transplant recipients, based on a Bayesian neural network model.

## 🚀 Key Features
- **Interactive Interface:** Dynamic switches to select clinical variables with clean visual effects.
- **Hover Explanations:** Detailed descriptions of each clinical variable that expand smoothly on hover.
- **Real-Time Calculation:** Dynamic total score with adaptive color coding according to the risk level (Low, Intermediate, High, and Very High).
- **Reset Button & Security:** Quick reset button and a 30-minute inactivity timer that automatically resets the form.
- **Responsive Design:** Optimized for any screen size (desktop and mobile devices), including the institutional logo of the University of Antioquia.

---

## 📊 Clinical Score Variables

| Clinical Variable | Points | Brief Description |
| :--- | :---: | :--- |
| **Lymphopenia** | **+5 pts** | Absolute lymphocyte count < 1,000 cells/µL. |
| **Kidney transplant rejection** | **+4 pts** | History of allograft rejection episode. |
| **Immunosuppression intensification** | **+3 pts** | Steroid pulses, increased dose, plasmapheresis, and/or anti-thymocyte globulin. |
| **Non-thymoglobulin induction** | **+2 pts** | Induction therapy using agents other than anti-thymocyte globulin. |
| **Male gender** | **+1 pt** | Biological male sex assigned at birth. |
| **Antimetabolites** | **-1 pt** | Concurrent use of antimetabolite medications (Mycophenolate or Azathioprine). |

---

## 📈 Risk Stratification
- **≤ 2 pts (Low Risk):** Estimated probability of Cryptococcosis < 8.9%, with 95% sensitivity.
- **3 - 7 pts (Intermediate Risk):** Estimated probability between 8.9%–39.5%, sensitivity of 66%–95%, and specificity between 43%–85%.
- **8 - 14 pts (High Risk):** Estimated probability between 39%–85% with specificity > 85.5%.
- **15 pts (Very High Risk - ⚠️ Alert!):** Estimated probability > 85% with 98.4% specificity.

---

## 🛠️ Technologies Used
- **HTML5**
- **Tailwind CSS** (CSS styling framework via CDN)
- **JavaScript** (Client-side interactive logic and timers)

---

## 🌐 Live Link (GitHub Pages)
You can test the web application directly online at the following link:  
👉 [View Live Application](https://your-username.github.io/repository-name/) *(Replace this link with your GitHub Pages URL)*

---

## 📚 Reference & Authors
* **Study:** *Machine Learning and Clinical Scoring for Cryptococcosis Prediction in Kidney Transplant Recipients: A Bayesian Neural Network Model*
* **Authors:** Diego Oquendo-Gaona, Jhongert Alza-Arcila, Isabel Ramírez Sánchez
* **Institution:** Division of Infectious Diseases, Universidad de Antioquia, Colombia.