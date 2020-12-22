# Machine Learning Understanding
<img src="../master/images/Abstract logo.png" align="right" width="300" height="250" /> 

I am using the excellent book of Aurélian Géron "Hands-On Machine Learning with Scikit-Learn and TensorFlow", Scikit learn, TensorFlow and Keras documentation & code examples to discover both the ML theory and its techniques. Stack Overflow and Google are always helpful. 

`Weisstein, Eric W. "Chair Surface." From MathWorld--A Wolfram Web Resource. https://mathworld.wolfram.com/ChairSurface.html`

<table>
    <tbody>
         <tr>
            <td><a href="../master/Credit Card Fraud Detection.ipynb">9. Credit Card Fraud Detection (<b>Imbalanced Classification</b>)</a>
                <br> <b>General:</b> warnings.filterwarnings
                <br> <b>NumPy:</b> bincount, random.choice, concatenate
                <br> <b>SkLearn:</b> class_weight
            </td>
            <td><img src="../master/images/credit_card_fraud_pic.png" width="200" height="150" /></td>
        </tr>
        <tr>
            <td><a href="../master/Twitter Airline Sentiment.ipynb">8. Twitter Airline Sentiment (<b>Text Classification</b>) with <br>       GloVe word embeddings</a>
                <br> <b>General:</b> io.open
                <br> <b>NumPy:</b> array, fromstring, zeros, argmax
                <br> <b>matplotlib:</b> filter
                <br> <b>TensorFlow & Keras:</b> TextVectorization, get_vocabulary, Embedding, <br> sparse_categorical_crossentropy
            </td>
            <td><img src="../master/images/twitter_airline_sentiment_pic.png" width="200" height="150" /></td>
        </tr>
        <tr>
            <td><a href="../master/CIFAR-10 Image Classification.ipynb">7. CIFAR-10 <b>Image Classification using Keras</b></a>
                <br> <b>General:</b> pickle, decode
                <br> <b>NumPy:</b> reshape, transpose
                <br> <b>DataFrame:</b> astype
                <br> <b>matplotlib:</b> imshow
                <br> <b>TensorFlow & Keras:</b> to_categorical, Conv2D, BatchNormalization, <br> GlobalAveragePooling2D, callbacks.ModelCheckpoint
            </td>
            <td><img src="../master/images/cifar-10-pic.png" width="200" height="150" /></td>
        </tr>
         <tr>
            <td><a href="../master/Boston Housing Regression.ipynb">6. Boston Housing <b>Regression using Keras</b></a> 
                <br> <b>TensorFlow & Keras:</b> layers, Sequential, model.compile, summary, <br> plot_model, model.fit, history, EarlyStopping, <br> model.evaluate, TensorBoard
            </td>
            <td><img src="../master/images/boston_housing_pic.png" width="200" height="150" /></td>
        </tr>
        <tr>
            <td><a href="../master/Avila Classification.ipynb">5. Avila <b>Dimensionality Reduction<b/></a>
                <br> <b>Pandas:</b> to_numeric
                <br> <b>DataFrame:</b> replace
                <br> <b>matplotlib:</b> axes3d, view_init, get_cmap, add_subplot
                <br> <b>SkLearn:</b> PCA, explained_variance_ratio_, LocallyLinearEmbedding, <br> TSNE, make_swiss_roll, MDS, DBSCAN, KMeans
            </td>
            <td><img src="../master/images/avila_pic.png" width="200" height="150" /></td>
        </tr>
        <tr>
            <td><a href="../master/Motion Capture Hand Postures.ipynb">4. Motion Capture Hand Postures (<b>Ensemble of classifiers</b>)</a>
                <br> <b>NumPy:</b> nan
                <br> <b>matplotlib:</b> scatter
                <br> <b>SkLearn:</b> SimpleImputer, RidgeClassifier, VotingClassifier, ExtraTreesClassifier
            </td>
            <td><img src="../master/images/motion_capture_pic.png" width="200" height="150" /></td>
        </tr>
        <tr>
            <td><a href="../master/Arcene Cancer Classification.ipynb">3. Arcene Cancer Binary Classification using <b>SVM</b></a>
                <br> <b>NumPy:</b> ravel
                <br> <b>Pandas:</b> concat
                <br> <b>DataFrame:</b> T, iloc
                <br> <b>SkLearn:</b> LinearSVC, SVC, RandomForestRegressor
            </td>
            <td><img src="../master/images/arcene_cancer_pic.png" width="200" height="150" /></td>
        </tr>
        <tr>
            <td><a href="../master/Epileptic Seizure Classification.ipynb">2. Epileptic Seizure <b>Binary & Multi-class Classification</b></a>
                <br> <b>NumPy:</b> shape, random.permutation, fill_diagonal
                <br> <b>DataFrame:</b> rename, copy
                <br> <b>matplotlib:</b> pyplot, figure, legend, matshow
                <br> <b>SkLearn:</b> SGDClassifier, confusion_matrix, precision_score, <br> recall_score, f1_score, precision_recall_curve, <br> roc_curve, RandomForestClassifier
            </td>
            <td><img src="../master/images/epileptic_seizure_pic.png" width="200" height="150" /></td>
        </tr>
         <tr>
            <td><a href="../master/Bike Sharing Regression.ipynb">1. Bike Sharing <b>Regression</b></a>
                <br> <b>Pandas:</b> read_csv
                <br> <b>DataFrame:</b> head, describe, hist, plot, drop, corr
                <br> <b>SkLearn:</b> train_test_split, OneHotEncoder, Pipeline, StandardScaler,<br> LinearRegression, mean_squared_error, DecisionTreeRegressor, fit, predict,<br> cross_val_score, GridSearchCV, RandomizedSearchCV, <br> feature_importances_
            </td>
            <td><img src="../master/images/bike_sharing_pic.png" width="200" height="150" /></td>
        </tr>
    </tbody>
</table>


<table>
    <thead>
        <tr>
            <th colspan="2">My development environment</th>
        </tr>
        <tr>
            <th>Name</th>
            <th>Version</th>
        </tr>
    </thead>
    <tbody>   
         <tr>
            <td>Python</td>
            <td>3.7.7</td>
        </tr>
        <tr>
            <td>scikit-learn</td>
            <td>0.22.1</td>
        </tr>
         <tr>
            <td>IPython</td>
            <td>7.15.0</td>
        </tr>
        <tr>
            <td>Jupyter notebook</td>
            <td>6.0.3</td>
        </tr>
        <tr>
            <td>TensorFlow</td>
            <td>2.1</td>
        </tr>
    </tbody>
</table>
