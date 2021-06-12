# CS-282
## Creating custom dataset
### Torch Dataset
The main task of the Dataset class is to return a pair of [input, label] every time it is called. We can define functions inside the class to preprocess the data, and return it in the format we require.

The torch dataset class can be imported from torch.utils.data.Dataset

### Torch Dataloader
The Torch Dataloader not only allows us to iterate through the dataset in batches, but also gives us access to inbuilt functions for multiprocessing(allows us to load multiple batches of data in parallel, rather than loading one batch at a time), shuffling, etc.

The torch dataloader class can be imported from torch.utils.data.DataLoader

