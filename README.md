
# Resume-Extraction
---

**Note -**
*Currently this project just works for pdf formatted resume*

---

## To download the dependencies
`pip install -r requirements.txt`

## This project requires spacy en_core_web_lg model
* To download it:
`python -m spacy download en_core_web_lg`

## Result
    {'name': 'Kumar Mangalam',
        'experience': 1.09,
        'education': 4.0,
        'skills': ['Java',
                    ' SQL',
                    ' Python',
                    'Bootstrap',
                    ' jQuery',
                    ' d3.js',
                    '\xa0 HTML5',
                    ' CSS3',
                    ' Javascript',
                    '\xa0 Kibana',
                    'MongoDB',
                    ' OrientDB',
                    ' MySQL',
                    '\xa0 ElasticSearch',
                    'Docker',
                    ' gUnicorn',
                    ' Nginx',
                    '\xa0 Airflow',
                    'Pandas',
                    ' Numpy',
                    ' Matplotlib',
                    '\xa0 Seaborn',
                    ' Sklearn',
                    ' OpenCV',
                    '\xa0 Tensorflow',
                    'RNN',
                    ' LSTM',
                    ' CNN',
                    ' Attention',
                    '\xa0 Transformer',
                    ' YOLO',
                    ' SNN',
                    '\xa0 Transfer learning',
                    ' Statistical\xa0 classification'],
        'mail_id': 'manguatwork@gmail.com',
        'contact_number': '9876543210'}

## few case are not catered yet:
<ul>
    <li>([('2018', '2018'),('2013', '2013')], [])</li>
    <li>([('2018.001-2019.009', '1.008'),('2013', '2013')], [])</li>
</ul>
