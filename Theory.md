>>Data manipulation:
If our program we do a valid or invalid mistake for fixing that and cleaning some data in our program is data manipulation means making changes in data of our programme.

>>Data analysis:
Find data pattern and solve problems with the help of data in our programme , it did'nt making any change in data just do problem using that data and finding something in that data.

>>pandas:
created by wes Mckinney in 2008 beacause while working at AQR capital management,wes faced challenges while analyzing financial datasets before this data scientists uses exisisting        tools like excel for large scale data cleaning and analysis so , panadas is powerfull and popular library  used for data manipulation and data analysis .

>Key features:
1. work seamlessly with structured formates like csv and Excel.
2. handles missing values easilly.
3. Built on numpy for fast computation.

>              why python used?
1. Perfomance:  

       handles millions of rows efficiantly.
2. Ease of use:
 
          Beginner-friendly syntax for cleaning and transforming data.

3. Integration:

        works with libararies like Motplotib(visualization) and sikit-learn (machine learning).


>                  Key Concepts on pandas
1. SERIES:

        .A series is a one-dimensional labeled array that can hold any data type :Integers , floats ,strings,or even python object. Each element in the series has unique object label an object.
        
        .It is often used to track changes or patterns overtime,such as daily tempratures, stock revenue or sales revenue.
2. DATA FRAME:

        . A data frame is two dimensional labeled structure in pandas, similiar to table in data base, an excel spread sheet or a SQL table.

        . it is consists of rows and coloums, where:
              a.Rows have indices (labels)
              b.Coloums have have names (labels) 
3. Data Explore: 

>why we need to explore data?
1. Under the data set means how many rows/coloums, In which format data is present.
2. Identify the problems means  having incorrect data type or missing data something is missing.
3. Plan next steps, if we are aware about mistakes and problems of our data then we can plan next steps of our data easilly.
>how we explore data?
1. Exploring Rows and coloums :

        For exploring data we have to see the structure of that data, for that we have to see all rows and coloum one by one if our data has millions of rows and coloums then we have to use head and tail function that helps to see every row and coloum easilly one by one so, head function which gives us upper rows and in parenthis we have to pass how many rows  we need if we pass nothing in parenthisis then it gives five rows and coloums by default , Also for exploring lower rows and and coloums we use tail function same like haid  we have to pass no of rows and coloums in parenthesis and if we passed nothing in parenthesis then it takes five and gives  last five rows and coloums.
2. Identify data :
         
        we use Info method that helps us to find number of rows and coulms our data contains ,data belongs from which coloum/row ,our couloum/row has in which data type,    using this we can find missing data of our rows/coloums and  we  can  also find  memory  usage in that data frame, we have to just read that data in a variable and using that  we have use that method it will gives directly all these things.
        
        Also we have another method which is describe that gives us many things, first is count which gives us how many no of values in every coloumn, second is mean which gives result of total sum of all values devides by total no of those values means count values,third std which means standard daviation there are two type of small standard deviation means values have small gap between them means values of coloumn values should be nearest and if it gives large no gap between values of coloumn then it should be large standard daviation, fourth it gives min  means smallest value among all values in coloumn,25%,50%&75% so first it assign values in assending order means small to large then it checks first 25% values and it gives  another value which is greater than 25% values but less then middle values then 50% means middle value from all among all values in assending value after that 75% means last values it gives a middle number which is closer to last values which is 75% and last thing it gives max which means largest value among all values of a coloumn.

>Shape and coloumn:

        These are atributes using shape we find no of coloums and no rows in data and using coloumn we can find all names of couloumn and there data types, we use this like methods just variable name . that atributes and using these we can find details of long data sets easily.

>Selecting Coloums:
        
        If we need any specific coloumn data then we have to just write that data frame variable name and in box bracket in that write that coloumn name in double code if we want two or more than two coloumns data then in same way in box write these coloumn names in double codes and seprate this with commas.
>conditional selecting:

       if we want data of coloumn under a specific condition  so we use this format: variable_name[variable_name["coloumn_name"]comparasion_operator value] for multiple conditions we use this format: variable_name[(variable_name["coloumn_name"]comprasion_operator value)&(variable_name["coloumn_name"]comparision_oparater value)] also we use or condition using this | symbol at the place of &. 
>Adding coloumns:

      we can add new coloumns and their data in a data so for that we use that syntax : varibale_name["coloumn_name"]=data for that variable.

      we have another method for adding a variable which is insert using this we can add a coloumn at a specific index using this syntax of insert method variable_name.insert(index,"coloumn_name",data for that variable).
>Updating data:
        
        we can easilly changing the data of a specific coloumn using thisa syntax variable_name.loc[row_no,"coloumn_name"]=new_data.
>removing coloumns:
       we can easilly remove a specific removing using a pandas method for that we use that syntax: variable_name.drop(coloumns=["coloumn_name"],inpalace=True) so in parenthesis write coloumns assigns that variable_name comma inspect assgns True it means it directly remove that coloumn if we write False then it assign a new data and if we want to remove  more than one coloumns than we have just inside box bracket add comma and in double codes we can write many columns and it will remove that.
