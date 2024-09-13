# Proyek Akhir : HR Analisis Employ Attrition in Company Multinasional

Nama : Mufidatul Ngazizah

Email : mufidatul.ngazizah@gmail.com

## Businees Understanding

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Ia memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. 

Walaupun telah menjadi menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%.

Untuk mencegah hal ini semakin parah, manajer departemen HR ingin meminta bantuan Anda mengidentifikasi berbagai faktor yang mempengaruhi tingginya attrition rate tersebut. Selain itu, ia juga meminta Anda untuk membuat business dashboard untuk membantunya memonitori berbagai faktor tersebut.

## Permasalahan Bisnis
Masalah bisnis yang akan diselesaikan adalah

1. Lebih dari 10% karyawan Jaya Jaya Maju mengalami attrition (keluar dari perusahaan) karena perusahaan cukup kesulitan mengelola karyawan
2. Departemen HR tidak memiliki dashboard yang dapat memantau dan memonitor pengelolaan karyawan termasuk penyebab karyawan yang melakukan attritiion.

## Cakupan Proyek
1. Menganalisis kebutuhan perusahaan seperti :
   * Business Understanding
   * Data Understanding

2. Mengembangkan model yang terdiri dari beberapa tahap berikut:
   * Data Preparation
   * Modeling
   * Model Evaluation
   * Dashboard

## Persiapan
Sumber Data : Github https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee

Setup environment:
1. Pengguna membuka terminal dengan root yang telah ditentukan
2. Pengguna mengistall virtual env
   '''
   py -m pip install virtualenv
  '''
4. Penguna membuat virtual env
   '''
   python -m venv myenv
   '''
5. Jalankan virtual env
   '''
   myenv\Script\activate
   '''
7. Melakukan install library yang digunakan sesuai requirement.txt
8. Menjalankan jupiter notebook
9. Melakukan input data baru yang ingin diprediksi

### Metabase
Melakukan upload dataset ke Supabase untuk digunakan membuat dashboard di Metabase


### Keterangan Dataset
'''
Dataset yang berisi faktor-faktor yang mempengaruhi attrition

    EmployeeId - Employee Identifier
    Attrition - Did the employee attrition? (0=no, 1=yes)
    Age - Age of the employee
    BusinessTravel - Travel commitments for the job
    DailyRate - Daily salary
    Department - Employee Department
    DistanceFromHome - Distance from work to home (in km)
    Education - 1-Below College, 2-College, 3-Bachelor, 4-Master,5-Doctor
    EducationField - Field of Education
    EnvironmentSatisfaction - 1-Low, 2-Medium, 3-High, 4-Very High
    Gender - Employee's gender
    HourlyRate - Hourly salary
    JobInvolvement - 1-Low, 2-Medium, 3-High, 4-Very High
    JobLevel - Level of job (1 to 5)
    JobRole - Job Roles
    JobSatisfaction - 1-Low, 2-Medium, 3-High, 4-Very High
    MaritalStatus - Marital Status
    MonthlyIncome - Monthly salary
    MonthlyRate - Mounthly rate
    NumCompaniesWorked - Number of companies worked at
    Over18 - Over 18 years of age?
    OverTime - Overtime?
    PercentSalaryHike - The percentage increase in salary last year
    PerformanceRating - 1-Low, 2-Good, 3-Excellent, 4-Outstanding
    RelationshipSatisfaction - 1-Low, 2-Medium, 3-High, 4-Very High
    StandardHours - Standard Hours
    StockOptionLevel - Stock Option Level
    TotalWorkingYears - Total years worked
    TrainingTimesLastYear - Number of training attended last year
    WorkLifeBalance - 1-Low, 2-Good, 3-Excellent, 4-Outstanding
    YearsAtCompany - Years at Company
    YearsInCurrentRole - Years in the current role
    YearsSinceLastPromotion - Years since the last promotion
    YearsWithCurrManager - Years with the current manager
    
'''
## Business Dashboard

![Dashboard HR.](https://github.com/mufidatuln/Belajar-Penerapan-Data-Science-HR-Analisis/blob/main/HR%20Analysis_page-0001.jpg)

Analisis Dashboard Data yang digunakan berfokus pada karyawan yang melakukan attrition (attrition = 1 or Yes) dengan tujuan mengetahui faktoe yang memnyebabkan keluarnya karyawan dari perusahaan.
1. 
