<div align="center">

  <h1>🎓 SRM VEC CGPA & GPA</h1>
  
  <p>
    <strong>A next-generation GPA & CGPA algorithmic engine engineered for the R-2023 Regulations.</strong><br>
    Built with a premium <i>Midnight Zinc</i> UI and dynamic curriculum data routing.
  </p>

  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  </p>

</div>

---

## ⚡ What This Calculator Does

This application automates the tedious and error-prone process of calculating college grades by digitizing the entire institutional rulebook. 

* 🏛️ **11-Department Database:** Pre-loaded with the exact subjects, credits, and categories for every department across all 8 semesters.
* 🧠 **Smart Regulation Logic:** Automatically identifies and filters out 0-credit Mandatory Courses (like NSS, YRC, NCC) to ensure 100% mathematical accuracy without user intervention.
* 📈 **Instant CGPA Merging:** Takes previous cumulative data and instantly merges it with current semester performance to output a live-updated CGPA.
* 🖨️ **Export Ready:** Built-in functionality to instantly print or save semester results as a PDF for easy sharing.

<br>

## 🔌 Why an ECE Student Built This: "Because I Can."

People often ask why an Electronics and Communication Engineering student is building full-stack web applications. The short answer? **Because I can.** Engineering is about identifying inefficient systems and building better ones. Here is why the ECE mindset makes building an application like this second nature:

1. **Logic is Universal:** The core of ECE is pure logic. If you can design the FSM control unit for a 16-bit RISC processor or optimize a Booth multiplier at the gate level, writing JavaScript algorithms to dynamically route an 88-semester database is light work.
2. **Systems-Level Architecture:** ECE students are trained to see the whole system—from the bare-metal hardware to the software interface. Building a web app is simply translating that systems-level architecture into a new medium.
3. **The Full-Stack Hardware Engineer:** Modern electronics don't exist in a vacuum. Whether it's an IoT dashboard or an embedded systems interface, the ability to build beautiful, responsive front-ends to interact with complex backend logic is what separates a good engineer from a great one.
4. **Execution:** The existing GPA calculation process was tedious. I had the technical capability to automate it for the entire college, so I executed it.

<br>

## ⚙️ The Mathematical Engine

The logic utilizes the official R-2023 10-point grading scale. The algorithm automatically skips non-credit courses to maintain data integrity.

| Grade | Letter | Points | Classification |
| :---: | :--- | :---: | :--- |
| **O** | Outstanding | **10** | First Class with Distinction |
| **A+** | Excellent | **9** | First Class with Distinction |
| **A** | Very Good | **8** | First Class |
| **B+** | Good | **7** | First Class |
| **B** | Average | **6** | First Class |
| **C** | Satisfactory | **5** | Pass Class |
| **U** | Reappear | **0** | Arrear / Fail |

<br>

## 🚀 Deployment Pipeline

This repository is optimized for continuous integration (CI/CD) using **GitHub** and **Vercel**. 

1. Code is pushed to this public GitHub repository.
2. Vercel automatically detects commits to the `main` branch.
3. The live production URL is instantly updated with zero downtime or manual rebuilds required.

---

<div align="center">
  <p><i>Disclaimer: This is a student-built utility tool and is not officially affiliated with SRM Valliammai Engineering College administration. Always cross-reference with your official mark sheets.</i></p>
</div>
