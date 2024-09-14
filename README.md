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
Sumber Data : [Github](https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee)

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

Analisis Dashboard Data yang digunakan berfokus pada karyawan yang melakukan attrition (attrition = 1 or Yes) dengan tujuan mengetahui faktor yang memnyebabkan keluarnya karyawan dari perusahaan.
1. Jumlah Karyawan yang keluar dari perusahaan tersebut sejumlah 179 karyawan yang mana adalah 17% dari semua karyawan.
   
2. Karyawan yang mengalami attrition lebih banyak merupakan karyawan bergender male (laki-laki)
  
3. Karyawan sejumlah 98 keluar dan mengalami overtime dalam bekerja. Dari total semua karyawan yang keluar di dominasi oleh karyawan yang bekerja overtime.
   
4. Karyawan yang keluar merupakan karyawan yang jarang melakukan bisnis travel.
  
5. Performance rating semua karyawan yang keluar tidak memiliki jejak performa buruk. Semua berada pada niali 3 dan 4 yang artinya 3-Excellent, 4-Outstanding.
   
6. Karyawan yang keluar didominasi oleh karyawan yang memiliki pendapatan bulanan di range 1000$ sampai 8000$

7. Berdasarkan analisis yang dilakukan mayoritas karyawan yang keluar memiliki tingkatan  Kepuasan Terhadap Lingkungan Kerja (EnvironmentSatisfaction) yang 1 = rendah (Low) terhadap kepuasan lingkungan kerja.

8. Berdasarkan analisis yang dilakukan mayoritas karyawan yang keluar memilki riwayat pendidikan dengan nilai 3 yaitu sebagai  Sarjana (Bachelor) 

9. Berdasarkan grafik karyawan yang keluar di dominasi oleh karyawan pada departement Research & Development.

10. Status Pernikahan karyawan yang keluar di dominasi oleh status Single.

11. Berdasarkan analisis yang dilakukan mayoritas karyawan yang keluar berada pada usia 30-35 sebanyak 44 orang diikuti usia 25-30 sebanyak 41 orang.

12. Berdasarkan grafik departemen Research & Development merupakan sumber terbesar karyawan yang keluar dari perusahaan.

13. Berdasarkan analisis yang dilakukan mayoritas karyawan yang keluar berjarak 2-3 KM dari rumah sebanyak 22 orang, diikuti jarak 1-2 KM sebanyak 20 orang.

## Conclusion
Berdasarkan analisis yang dilakukan terdahap data attrition karyawan, terdapat faktor yang mempengaruhi attrition kayawan. Berikut kesimpulan yang dapat diperoleh dari analisis tersebut:
1. Berdasarkan Jam Bekerja (Over Time)
   * Sebanyak 55% karyawan yang keluar mengalami over time dalam bekerja
   * Hal ini menunjukan bahwa karyawan yang memiliki jam bekerja over time cenderung memiliki kemungkinan attrition yang tinggi. Perusahaan mungkin dapat membuat kebijakan dan peraturan lebih baik terkait jam kerja agar karyawan tidak mengalami overtime dalam bekerja.
  
2. Berdasarkan Gender
   * Mayoritas karyawan yang keluar adalah laki-laki.
   * Hal tersebut menunjukkan adanya kemungkinan masalah yang lebih mempengaruhi karyawan laki-laki dibandingkan perempuan, atau bisa juga menunjukkan bahwa proporsi karyawan laki-laki yang lebih tinggi di perusahaan.

2. Berdasarkan Business Travel
   * Sebanyak 117 karyawan dengan status Rarely Travel mengalami attrition dan 51 karyawan dengan status Travel_Frequently juga mengalami attrition.
   * Dari hal tersebut kita tidak dapat menyimpulkan bahwa dengan menaikan frekuensi bisnis travel akan mencegah attrition pada karyawan karena karyawan dengan status frequently travel juga mengalami attrition. Mungkin perusahaan dapat mencari faktor lain yang dapat mencegah attrition karyawan.

3. Berdasarkan Performa Rating
   * Seluruh karyawan yang mengalami attrition memiliki performa Excellent (16%) dan Outstanding (84%)
   * Hal ini menunjukkan bahwa karyawan dengan performa tinggi cenderung meninggalkan perusahaan, yang mungkin mengindikasikan ketidakpuasan meskipun kinerja mereka sangat baik.

4. Berdasarkan Montly Income (Gaji Bulanan)
   * Attrition terbanyak di dominasi oleh karyawan dengan montly salary (gaji bulanan) pada rentang 2000$-4000$ yaitu sebanyak 92 karyawan.
   * Hal tersebut menandakan bahwa karyawan yang mengalami attrition adalah karyawan yang mungkin tidak puas dengan gaji yang diberikan.
  
5.  Berdasarkan Environment Satisfaction
   *  Mayoritas karyawan yang keluar memiliki tingkat kepuasan yang rendah (Low) terhadap lingkungan kerja.
   *  Hal ini menunjukkan bahwa peningkatan kepuasan terhadap lingkungan kerja bisa menjadi langkah penting dalam mengurangi attrition.

6. Berdasarkan Education
   * Mayoritas karyawan yang keluar memiliki tingkat pendidikan Sarjana (Bachelor).
   * Hal ini dapat menunjukkan bahwa karyawan dengan pendidikan Sarjana mungkin merasa kurangnya kesempatan untuk menggunakan atau mengembangkan keterampilan mereka di perusahaan dan perlu dianalisis lebih lanjut.

7. Berdasarkan Marital Status
   * Berdasarkan Status Pernikahan karyawan yang mengalami attrition ialah karyawan yang masih single.
   * Hal ini menunjukan bahwa karyawan single masih memiliki kesempatan dan keinginan untuk mengeksplore karir lebih lanjut di perusahaan lain yang memiliki kualitas lebih baik dari segi lingkungan maupun gaji.
  
8. Berdasarkan Age (Umur)
   * Karyawan yang keluar kebanyakan berusia 31-32 tahun, diikuti oleh usia 29-30 tahun.
   * Hal ini dapat menunjukkan bahwa rentang usia ini seringkali merupakan periode dalam karir ketika karyawan mencari peluang pengembangan lebih lanjut atau peningkatan karir yang mungkin tidak mereka temukan di perusahaan saat ini.
  
9. Berdasarkan Departement
    * Departemen Research & Development merupakan sumber terbesar karyawan yang keluar dari perusahaan.
    * Hal ini bisa mengindikasikan masalah spesifik dalam departemen tersebut, seperti budaya kerja, beban kerja, atau manajemen.
  
10. Berdasarkan Distance From Home
    * Karyawan yang keluar kebanyakan tinggal pada jarak 2-3 KM dari kantor, diikuti oleh 1-2 KM.
    * Hal ini dapat mengindikasikan bahwa jarak yang dekat tidak cukup untuk mempertahankan karyawan jika faktor-faktor lain seperti kepuasan kerja dan pengembangan karir tidak terpenuhi.

11. Berdasarkan hasil training dan evaluasi yang dilakukan pada beberapa model. Evaluasi model terbaik terdapat pada Gradient Boosting.


# Rekomendasi Action 

1. Memperbaiki masalah over time pada karyawan dengan mengurangi jam lembur dan menerapkan kebijakan yang dapat mengatasi hal tersebut
2. Fokus dengan karyawan yang sudah memiliki kinerja bagus dengan mengidentifikasi penyebab ketidakpuasan karyawan.
3. Menaikan gaji karyawan dengan performa sangat baik (excellent) sehingga sesuai dengan ekspektasi gaji yang mereka harapkan dan sesuai dengan pekerjaan yang telah dilakukan.
4. Melakukan survey pada karyawan untuk mengetahui penyebab secara spesifik terkait kepuasan karyawan pada lingkungan kerja dengan menyebarkan pertanyan spesifik dan mendengarkan aspirasi maupun saran dari karyawan tersebut.
