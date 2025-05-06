
#  6-DOF Industrial Robot Kinematics Visualization

This project simulates and visualizes the 3D motion path of an ABB IRB 2400 6-axis industrial robot using real joint angle data. It includes joint angle trajectory plots and a 3D forward kinematics path estimation.

---

## 📁 Dataset

- **Source**: [Kaggle – ABB IRB 2400 Arm Kinematics Dataset](https://www.kaggle.com/datasets/luisatencio/abb-irb-2400-arm-robot-kinematics-dataset)
- Contains joint angle data (`q1_in` to `q6_in`, `q1_out` to `q6_out`) and 3D pose info.

---

## 📌 Features

- Visualizes individual joint angle trajectories (`q*_out`)
- Simulates forward kinematics using simplified 3DOF model
- Plots the 3D end-effector path
- Data preprocessed and downsampled for clarity
- Ready to extend into inverse kinematics or robot animation

---

## 📊 Visual Outputs

- 📈 Joint trajectory subplots (6 separate charts)
- 🧭 Simulated 3D end-effector path with realistic scaling

---

## 🛠 Technologies

- Python, Pandas, NumPy, Matplotlib (3D plots)
- Dataset via Kaggle

---

## 🚀 How to Run

1. Download the dataset from Kaggle
2. Place `datasetIRB2400.csv` in the project folder
3. Run the Jupyter/Colab notebook to see visualizations

---

## 📌 Example Output

![3D Path](./example_output_3d_path.png)

---

## 📜 License

This project is for educational and research purposes.
"""

# Write to README.md
with open("README.md", "w") as f:
    f.write(readme_content)

print("✅ README.md created.")
