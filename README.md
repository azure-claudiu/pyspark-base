Dev container for pyspark work
------------------------------

# Optional setup

Although not necessary, these environment variables might be useful:

```
export SPARK_HOME=/opt/conda/lib/python3.9/site-packages/pyspark
export PYTHONPATH=$SPARK_HOME/python:$SPARK_HOME/python/build:$PYTHONPATH
```

# Dependencies

To see the version of pyspark installed:

```
pip show pyspark
```

Although the dev container ensures the correct python runtime, you can prefix any .py script with this line:

```
#!/opt/conda/bin/python
```
