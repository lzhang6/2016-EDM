# 2016-EDM
Source code and data sets for 2016 EDM

### Dependencies:
- Tensorflow 0.10 (only tested on this version)
- Numpy
- scikit-learn

### Get Started

```
git clone https://github.com/siyuanzhao/2016-EDM.git
cd 2016-EDM
python student_model.py
```

To run model on different dataset, change train_data_path and test_data_path in student_model.py

Data sets we used from the paper are in folder data.

<table>
<tr>
  <th></th>
  <th>ASSISTments 09-10 (a)</th>
  <th>ASSISTments 09-10 (b)</th>
  <th>ASSISTments 09-10 (c)</th>
</tr>
<tr>
  <td>file name</td>
  <td>0910_a</td>
  <td>0910_b</td>
  <td>0910_c</td>
</tr>
<tr>
  <td>Has duplicated records</td>
  <td>No</td>
  <td>No</td>
  <td>No</td>
</tr>
<tr>
  <td>Has subproblems</td>
  <td>Yes</td>
  <td>No</td>
  <td>No</td>
</tr>
<tr>
  <td>Repeat sequnces for mutiple skills</td>
  <td>Yes</td>
  <td>Yes</td>
  <td>No</td>
</tr>
<tr>
  <td>Combined skills for mutiple skills</td>
  <td>No</td>
  <td>No</td>
  <td>Yes</td>
</tr>
</table>

CAT_train.csv and CAT_test.csv are data files from Cognitive Tutor.
