# json2excel
automatic make json data to excel file
# how to use
params:
```
file_name: ./xxx.xlsx(your excel file path )
sheets: your data like:
    [{'title':'sheet0', # sheet name
       'headers':{'name':'姓名','age':'年龄'}, # first column
       'data_list': # main data list 
       [ 
            {'name':'admin','age':12},
            {'name':'guest','age':12},
       ]}]
```
return:
```
file_name
```