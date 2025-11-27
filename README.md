# mljs-mobile
Machine Learning algorithms in JavaScript for browser environments.

A lightweight collection of machine learning algorithms implemented in pure JavaScript for use directly in the browser.  
Includes K-Nearest Neighbors, Logistic Regression, Linear Regression, and CSV loading utilities.

---

## 🚀 Quick Start Demo

1. Open the `examples/` folder.
2. Launch `index_loadcsv.html` in your browser.
3. Upload any CSV file OR use the hard-coded sample data.
4. Open the browser console to see predictions/output.

A new interactive example is included to demonstrate running Logistic Regression end-to-end.

---

## 📖 Usage Example

<!-- Usage example -->
<script src="logistic-regression.js"></script>
<script>
  const X = [[1, 2], [2, 3], [3, 4]];
  const y = [0, 0, 1];

  const logReg = new LogisticRegression();
  logReg.train(X, y, 0.1, 200);

  const prediction = logReg.predict([2.5, 3.5]);
  console.log("Prediction:", prediction);
</script>
