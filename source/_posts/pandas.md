
# 利用Python进行数据分析
主要介绍pandas与numpy的数据统计法，可视化方法等。


    import pandas
    import sys
    
    columns = ['label', 'price', 'rank', 'rate', 'date', 'a','b','c','d','e','f','g','h','score','j']
    
    dataframe1 = pandas.read_csv(r"d:\tmp\1.txt",encoding='utf-8',
                                    names=columns, sep='\t')
    dataframe1.describe()

    C:\Users\sijia.lai\AppData\Local\Continuum\Anaconda\lib\site-packages\pandas\io\parsers.py:1170: DtypeWarning: Columns (11) have mixed types. Specify dtype option on import or set low_memory=False.
      data = self._reader.read(nrows)
    




<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>label</th>
      <th>b</th>
      <th>h</th>
      <th>score</th>
      <th>j</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>104104.000000</td>
      <td>104104.000000</td>
      <td>104104.000000</td>
      <td>104104.000000</td>
      <td>104104.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>0.027713</td>
      <td>0.027713</td>
      <td>0.974088</td>
      <td>0.025912</td>
      <td>0.027713</td>
    </tr>
    <tr>
      <th>std</th>
      <td>0.164149</td>
      <td>0.164149</td>
      <td>0.002570</td>
      <td>0.002570</td>
      <td>0.164149</td>
    </tr>
    <tr>
      <th>min</th>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.578660</td>
      <td>0.020166</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.973182</td>
      <td>0.024965</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.973822</td>
      <td>0.026178</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.975035</td>
      <td>0.026818</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>0.979834</td>
      <td>0.421340</td>
      <td>1.000000</td>
    </tr>
  </tbody>
</table>
</div>




    
