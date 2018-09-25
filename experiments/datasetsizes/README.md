#This experiment evaluates how our umbu-caja version behaves as the dataset grows

## Run

To run this test in your machine, you should use the following commands:

```
./setup
./runtest
```

Make sure you have at least 200Mb of disk space available. Results will be inside folder 'execute/'.

## Information about input

1. Sizes: 4.2GB, 8.7B, 16.2GB
2. Dimensions: 23000 x 23000, 33000 x 33000, 45000 x 45000 
3. Distinct elements: 23000, 33000, 45000
4. Origin: Randomly generated (once 'setup' is executed)
5. Environment: Octacore, 8GB RAM