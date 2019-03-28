# Start Data Science | Pandas X MySql
<p> This project of my case study for Data Science use Jupyter and other tools, I hope from this litle docs help another you need for learn process, thanks</p>

# Connecting to Mysql Database

<ul>
    <li>
        <p>First, Install <a href="https://dev.mysql.com/doc/connector-python/en/connector-python-installation.html">MySql Python Connector</a> 
        </p>
        <code>$ pip install mysql-connector-python</code> 
    </li>
    <li>
        <p>After installation process done, you can try this code : </p>
        <ul>
            <li>
                <p>Connect to Mysql Database and test with print()</p>
                <img src="./preview/connect_to_mysql.png">
            </li>
        </ul>
    </li>
</ul>

# Select Table & Column

<ul>
    <li>
        <p>
            Select table with sql("select * from name_table"), but Firstly, add library or pandas tools for make cool data visualization
        </p>
        <code>$ import pandas as another_aliases</code>
        <p>for this example use <b>DataFrame</b></p>
        <img src="./preview/select_table_preview_with_pandas.png">
    </li>
    <li>
        <p><b>Select Column</b> Or Filtering(index & select data)</p>
        <p>
            # Select one column
        </p>
        <img src="./preview/select_column_as_name_column.png">
        <br>
        <p>
            # Select multiple column
        </p>
            <img src="./preview/select_multiple_column.png">
    </li>
    <li>
        <p><b>Checking Data Type of Visualization</b></p>
        <p>
            if you want to chek type data visualization, just simple. you can check with general code on python, 
            and enter
        </p>
        <code> $ type(variable_data_name)</code>
        <p>then you can see type of data visualization used.</p>
        <img src="./preview/select_column_as_name_column.png">
    </li>
</ul>


