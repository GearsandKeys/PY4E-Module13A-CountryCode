# Exercise 1: 
Print out the two-character country code from the retrieved data. 
Add error checking so your program does not traceback if the country code is not there. 
Once you have it working, search for “Atlantic Ocean” and make sure it can
handle locations that are not in any country.

You may do this using JSON or XML.

The original examples were infinite loops, write your function to run only once.

# Example
```
Enter location: Kansas City, MO
Country Code: US
```

```
Enter location: Brazil
Country Code: BR
```

```
Enter location: Atlantic Ocean
No country code found.
```

# Tip
Looks at the json and xml example. 
That said, feel free to explore getting yourself an api key and feel free to experiment with the requests library!

# Test
test_get_geo_codes.py contains test code.  When all tests pass, you are good to go.  You can run the file using pytest.
