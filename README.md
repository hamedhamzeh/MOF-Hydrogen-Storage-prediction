<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>ML-Driven Hydrogen Storage Models</h1>

<p>This repository contains the code, dataset, and documentation for the project titled <strong>"ML-Driven Hydrogen Storage Models"</strong>. The primary goal of this project is to develop and optimize alternative models for hydrogen storage using machine learning techniques. This project specifically focuses on using Metal-Organic Frameworks (MOFs) to enhance hydrogen storage capacity.</p>

<p><strong>Achievement:</strong> This project earned me the <strong>First Place</strong> in the <em>National Competition</em> held by Iran’s National Elites Foundation. The competition was focused on the <em>Research and Development of a Machine Learning Model capable of Detecting and Proposing the Proper Hydrogen Adsorbent</em>.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#introduction">Introduction</a></li>
    <li><a href="#about-dataset">About Dataset</a></li>
    <li><a href="#modeling-approach">Modeling Approach</a></li>
    <li><a href="#results-and-evaluation">Results and Evaluation</a></li>
    <li><a href="#conclusion">Conclusion</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#references">References</a></li>
</ul>

<h2 id="introduction">Introduction</h2>
<p>Hydrogen storage is a critical component of energy systems, particularly for renewable energy sources like wind and solar. The storage of hydrogen in a compact and safe manner is essential for its use in fuel cells and other applications. This project explores the use of AI models to predict and optimize the hydrogen storage capacity of MOFs, which are known for their high surface area and tunable porosity.</p>

<h2 id="about-dataset">About Dataset</h2>
<p>Data for this project was collected from various sources, including research papers and publicly available datasets on hydrogen storage and MOFs. The data underwent several preprocessing steps, including cleaning, feature selection, and transformation. The key features used in the modeling include:</p>

<ul>
    <li>Single Crystal Density (D)</li>
    <li>Pore Volume (PV)</li>
    <li>Gravimetric Surface Area (GSA)</li>
    <li>Volumetric Surface Area (VSA)</li>
    <li>Void Fraction (VF)</li>
    <li>Largest Cavity Diameter (LCD)</li>
    <li>Pore Limiting Diameter (PLD)</li>
</ul>
<p> You can download the cleaned dataset used in this project <a href="https://github.com/hamedhamzeh/MOF-Hydrogen-Storage-prediction/blob/main/CleanedData.csv" target="_blank">here</a>.</p>

<h2 id="modeling-approach">Modeling Approach</h2>
<p>Several AI models were developed and compared to predict the hydrogen storage capacity of MOFs. The models include:</p>
<ul>
    <li>Gradient Boosting Trees (GBT)</li>
    <li>K-Nearest Neighbors (KNN)</li>
    <li>LightGBM (LGBM)</li>
    <li>Random Forest (RF)</li>
    <li>Multilayer Perceptron (MLP)</li>
    <li>XGBoost (XGB)</li>
</ul>
<p>The modeling process involved hyperparameter optimization using <strong>Optuna</strong>, model training, and evaluation using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).</p>

<h2 id="results-and-evaluation">Results and Evaluation</h2>
<p>The results showed that certain models outperformed others in predicting both gravimetric and volumetric hydrogen storage capacities. For example, models like Random Forest and XGBoost provided the lowest MSE and RMSE values, indicating higher accuracy.</p>
<p><strong>Comparing Models Preformance</strong></p>
<img src="https://github.com/hamedhamzeh/MOF-Hydrogen-Storage-prediction/blob/main/images/Result_1.JPG" alt="Result Image 1" width="1000">
<img src="https://github.com/hamedhamzeh/MOF-Hydrogen-Storage-prediction/blob/main/images/Result_2.JPG" alt="Result Image 1" width="1000">
<img src="https://github.com/hamedhamzeh/MOF-Hydrogen-Storage-prediction/blob/main/images/Result_3.JPG" alt="Result Image 1" width="1000">
<img src="https://github.com/hamedhamzeh/MOF-Hydrogen-Storage-prediction/blob/main/images/Result_4.JPG" alt="Result Image 1" width="1000">


<h2 id="conclusion">Conclusion</h2>
<p>This project successfully developed and optimized AI models for predicting hydrogen storage capacity in MOFs. The results can significantly contribute to the development of more efficient hydrogen storage systems.</p>

<h2 id="contributors">Contributors</h2>
<p>This project was made possible through the collaborative efforts of a dedicated team. The contributors include:</p>
<ul>
    <li><strong>Hamed Hamzeh</strong> - <em>AI Developer</em>:developed AI models, and performed data analysis.</li>
    <li><strong>Amir Hosein Khalili</strong> - <em>Researcher</em></li>
    <li><strong>Zahra Izadi</strong> - <em>Materials Scientist</em>: Provided expertise on Metal-Organic Frameworks (MOFs) and contributed to feature selection.</li>
    <li><strong>Seyed Sina Razavi</strong> - <em>Researcher</em></li>
</ul>

<h2 id="references">References</h2>
<p>The project references several key studies in the field of hydrogen storage and MOFs, including:</p>
<ul>
    <li>B. Ghorbani, S. Zendehboudi, N. M. C. Saady, and M. B. Dusseault, “Hydrogen storage in North America: Status, prospects, and challenges,” J. Environ. Chem. Eng., vol. 11, no. 3, p. 109957, 2023, doi: 10.1016/j.jece.2023.109957.</li>
    <li>J. Yang, A. Sudik, C. Wolverton, and D. J. Siegel, “High capacity hydrogen storage materials: Attributes for automotive applications and techniques for materials discovery,” Chem. Soc. Rev., vol. 39, no. 2, pp. 656–675, 2010, doi: 10.1039/b802882f.</li>
    <li>H. Furukawa, K. E. Cordova, M. O’Keeffe, and O. M. Yaghi, “The chemistry and applications of metal-organic frameworks,” Science, vol. 341, no. 6149, 2013, doi: 10.1126/science.1230444.</li>
</ul>

</body>
</html>
