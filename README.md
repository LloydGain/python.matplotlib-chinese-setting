# python.matplotlib-chinese-setting
setting chinese in plot

import matplotlib.font_manager as fm
prop = fm.FontProperties(fname='./SourceHanSansTW-Regular.otf') 

import matplotlib.pyplot as plt
plot = df.groupby('column1')['column2'].mean().plot(kind='bar')
ax.set_xticklabels( ['A','B'],fontproperties=prop)
plt.xticks(rotation=360)
