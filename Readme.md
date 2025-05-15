# IT Support Performance Prediction

This project uses dataset generated from typical IT Support metrics during my internship to predict employee performance using linear regression.

## 🔧 Internship Context
During my internship, I provided IT support to employees and clients. I tracked metrics such as:
- Average response time per ticket
- Number of tickets submitted per employee

These metrics were used to estimate how IT-related issues impact employee performance.

## 📊 Dataset

**File:** `it_support_data.csv`

**Columns:**
- `employee_id`: Unique ID for each employee
- `avg_response_time`: Average time taken to resolve support tickets (in hours)
- `num_tickets`: Number of support tickets submitted by the employee
- `performance_score`: Employee performance rating (0–100%)

**File:** `normalized_matrix.csv`  
Normalized version of the input features (with a bias term included) used for training.

## 🧠 Model

- Linear Regression using Gradient Descent
- Cost Function: Mean Squared Error (MSE)
- Learning Rate: 0.1
- Iterations: 500

## 📈 Results

Model performance on test data:
- **Test MSE**: *Displayed in notebook*
- **R² Score**: *Displayed in notebook*

## 🗂 Files

| File | Description |
|------|-------------|
| `it_support_data.csv` | The raw dataset |
| `normalized_matrix.csv` | Normalized input features |
| `IT_Support_Performance_Prediction.ipynb` | Jupyter notebook with all code steps |
| `README.md` | Project overview |

## 🔍 How Normalization Affects Feature Values

Normalization scales input features to a similar range (0 to 1), which:
- Prevents features with larger ranges from dominating the learning process
- Improves the convergence speed of gradient descent
- Stabilizes training across features

---

**Author:** *[USIH ELIJAH_20CJ027493]*  
**Internship Focus:** Information Technology Support  
**Institution:** *[COVENANT UNIVERSITY]*

