
# Resume-Extraction

## Currently this project just works for pdf formatted resume

## To download the dependencies
`pip install -r requirements.txt`

## This project requires spacy en_core_web_lg model
* To download it:
`python -m spacy download en_core_web_lg`


## few case are not catered yet:
<ul>
    <li>([('2018', '2018'),('2013', '2013')], [])</li>
    <li>([('2018.001-2019.009', '1.008'),('2013', '2013')], [])</li>
</ul>
