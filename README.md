# Graduate Electrical Engineer

## About Me

I am a **Master’s student in Electrical and Computer Engineering** at the **University at Albany, SUNY**, with a strong passion for **power systems, renewable energy, VLSI design, and digital systems**. My academic journey has equipped me with expertise in **circuit design, logic implementation, and electrical system analysis**. Currently, I serve as a **Teaching Assistant** and **Peer Tutor**, empowering students to master core engineering concepts.

I am actively seeking **full-time opportunities** in **Electrical Engineering, RTL Design, and VLSI domains** where I can leverage my technical knowledge and problem-solving skills to contribute meaningfully.

📍 Albany, NY | 📧 [akhilreddy1607@gmail.
---
## Education

- M.S., Electrical and Computer Engineering | University at Albany, State University of New York (_Expected May 2025_)
- B.Tech., Electrical and Electronics Engineering | Andhra University, India (Anil Neerukonda Institute of Technology and Sciences) (_2020-2023_)
- Diploma., Electrical and Electronics Engineering | Government Polytechnic Visakhapatnam, India (State Board of Technical Education & Training) (_2020_)
## Skills & Expertise

### **Technical Skills**

| Category              | Skills                                                               |
| ---------------------- | ------------------------------------------------------------------- |
| HDL Programming    | Verilog, SystemVerilog                                           |
| Electrical & Power Sys | Power System Analysis, Transformers, Electrical Wiring, MPPT Design |
| Design & Simulation   | AutoCAD, MATLAB Simulink, LTSpice, Cadence Tools, Magic VLSI, NGSpice |
| Programming       | Python, C, Socket Programming                             |
| Project Documentation | Technical Diagramming                                              |
| RTL Verification      | Cadence Xcelium                                                    |
| Power Electronics     | MPPT Design, Solar Array Simulation                                |

### **Certifications**

- AutoCAD 2022 & 2024 - LinkedIn Learning
- Semiconductor 101 v1.0 - Cadence

---

## Academic Projects

### **Baugh-Wooley Multiplier (MAGIC & SPICE) - Fall 2024**

- Designed and simulated a **2-bit Baugh-Wooley signed multiplier** using **hierarchical VLSI design** in MAGIC.
- Implemented basic cells (Full Adder, NAND, AND) and complex cells (CSA-W, CSA-G).
- Verified functionality with SPICE simulations, demonstrating correct operation for various input combinations.
- Achieved a **0.24 GHz maximum clock frequency** through critical path analysis.
- Ensured **DRC compliance** and extracted SPICE-compatible netlists.
- **Key Results:**
    - Simulation Cases: 0 x 0 = 0000, 1 x 1 = 0001, 1 x -1 = 0011 (-1 in decimal), -2 x -1 = 0010 (2 in decimal).
    - Maximum Clock Frequency: 0.24 GHz.
- **Tools:** MAGIC VLSI, NGSpice.
- **GitHub Repository:** [akhilreddygujju/baughwooley](https://github.com/akhilreddygujju/baughwooley)
- **Deployed Site:** [akhilreddygujju.github.io/baughwooley/](https://akhilreddygujju.github.io/baughwooley/)

### **1MW 1500V Solar Array Design and Simulation - Spring 2024**

- Designed and simulated a **1 MW solar array** for Albany, NY, adhering to a **1500V maximum DC voltage** constraint.
- Developed a **PV panel circuit model** using the "NES144/525-530 W F 35mm MBB Half-cell Mono solar cell" datasheet.
- Conducted **temperature analysis** using Albany, NY weather data to accurately model PV panel behavior.
- Performed **shading simulations** under uniform and non-uniform conditions, analyzing the impact on I-V and P-V characteristics.
- Compared **Central MPPT, MPPT per string, and MPPT per module** techniques under various shading scenarios.
- Generated **detailed I-V and P-V characteristic plots** and documented array design calculations.
- **Key Results:**
    - Calculated Voc at -8°C: 53.77V.
    - Calculated VMPP at 28°C: 48.89V.
    - Calculated IMPP at 28°C: 13.70A.
    - Maximum Power at 28°C: 670W.
    - Determined array design: 1493 panels, 27 series modules, 56 parallel strings.
    - Analyzed and compared MPPT performance under various shading conditions.
- **Tools:** MATLAB, Datasheet Analysis.
- **GitHub Repository:** [akhilreddygujju/pv](https://github.com/akhilreddygujju/pv)
- **Deployed Site:** [akhilreddygujju.github.io/pv/](https://akhilreddygujju.github.io/pv/)

### **Multiply-and-Accumulate (MAC) Unit & 4x4 Systolic Array (Verilog) - Spring 2024**

- Designed and implemented a **4x4 Systolic Array** for matrix multiplication in Verilog, drawing inspiration from the architectural principles of Google's Tensor Processing Units (TPUs) Toy Version.
- Developed a modular **Multiply-and-Accumulate (MAC) Unit** as the fundamental processing element within the systolic array, enabling efficient matrix operations.
- Conducted comprehensive functional verification using **Cadence Xcelium**, confirming the array's ability to accurately perform 4x4 matrix multiplications.
- Optimized the Verilog design to achieve a maximum clock frequency of **[Insert achieved clock frequency here]** through careful critical path analysis and timing closure techniques.
- Created detailed testbenches to rigorously validate the systolic array's performance across a diverse range of 4x4 input matrices
- **Tools:** Verilog, Cadence Xcelium.
- **GitHub Repository:** [akhilreddygujju/systolic-array](https://github.com/akhilreddygujju/systolic-array)
- **Deployed Site:** [akhilreddygujju.github.io/systolic-array/](https://akhilreddygujju.github.io/systolic-array/)

## **Instrumentation of a Three-Phase Transformer - Spring 2024**

- Designed the instrumentation for a 10MVA 66kV/13.8kV three-phase power transformer to monitor its input and output voltage, current, frequency, and power.
- Selected appropriate ratings for Current Transformers (CTs) and Potential Transformers (PTs) to scale down high voltage and current levels.
- Calculated burden resistor values for interfacing with monitoring circuitry.
- Developed a block diagram of analog and digital circuitry for measurement and monitoring.
- Identified part numbers from component manufacturers for selected instrument transformer ratings.
- **Key Results:**
    - Selected CTs: Primary (100/5A, GE 2DARL-101), Secondary (500/5A, GE Model 500).
    - Selected PTs: Primary (66kV/115V, JDCF JDCF-72.5W3), Secondary (13.8kV/110V, GE PTG5-1-110).
    - Calculated burden resistor values: 3 ohms (CTs), 73.52 ohms (Primary PT), 11.50 ohms (Secondary PT).
    - Developed block diagrams for voltage, current, power, and frequency measurement.
- **Tools:** Calculations, Datasheet Analysis.
- **GitHub Repository:** [akhilreddygujju/transformer-instrumentation](https://github.com/akhilreddygujju/instrument)
- **Deployed Site:** [akhilreddygujju.github.io/transformer-instrumentation/](https://akhilreddygujju.github.io/instrument/)

### **Cache Implementation & Reliable Data Transfer - Fall 2023**

- Implemented a **cache service** and **TCP/UDP protocols** for file exchange using Python.
- Analyzed protocol performance using **Wireshark** in a client-server architecture.

---

## Work Experience

### **Teaching Assistant | University at Albany** *(Jan 2024 - Dec 2024)*

- Assisted in **ECE 420 (VLSI), ECE 231 (Digital Systems), and ECE 202 (Circuits)**.
- Mentored **40+ students**, resulting in a **15% improvement in average VLSI lab scores**.
- Guided students in **Magic VLSI, NGSpice, and circuit simulation**.

### **Peer Tutor | University at Albany** *(Aug 2024 - Present)*

- Provided **one-on-one tutoring** for **ECE 202, ECE 231, and ECE 111**.
- Helped students with **problem-solving, exam preparation, and coursework**.

### **Facilities Operations Assistant | University at Albany** *(May 2024 - Aug 2024)*

- Assisted Union Painters in maintaining and refurbishing university facilities.
- Coordinated logistics, resource allocation, and event setup while ensuring safety compliance.

### **Electrical Engineer Intern | APTRANSCO** *(Jul 2022 - Aug 2022)*

- Gained hands-on experience with **220/132/33KV substations**, transformers, and circuit breakers.
- Conducted tests on Instrument Transformers and Cooling Fans of Power Transformers.

---

## Achievements

🏆 **Teaching Assistantship Award - University at Albany** *(Spring & Fall 2024)*<br>
🏆 **1st Place - Model Presentation Competition (Science Expo)** *(2022)*

---

## Let's Connect!

I am actively seeking **full-time opportunities in RTL design and VLSI, as well as roles in power systems and renewable energy**. If you have any relevant openings or would like to discuss potential collaborations, please reach out via **[LinkedIn](https://www.linkedin.com/in/akhil1607)** or email **[agujju@albany.edu](mailto:agujju@albany.edu)**.

I am open to discussing **full-time roles, research collaborations, and networking opportunities** in the fields of Electrical and Computer Engineering.
