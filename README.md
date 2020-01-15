# RNAseq_SortSeq tutorials 

Welcome to the tutorials repository for the RNAseq SortSeq project of the Rob Phillips Lab at Caltech! 

The tutorials are written in python and stored as jupyter notebooks. You can check them out in the `notebooks` folder.


## Run the tutorials in the cloud

You can click this [link](https://mybinder.org/v2/gh/RPGroup-PBoC/RNAseq_SortSeq/tutorials) (or the badge below) to start a Binder container of the repo. 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/RPGroup-PBoC/RNAseq_SortSeq/tutorials)


## Run the tutorials locally


All of the code use in this repo is python-based.
The library requirements can be installed by executing the following command using
[`pip`](pypi.org/project/pip) in the command line:

``` pip install -r requirements.txt ```

If you have `conda` you can also install the libraries by creating a conda environment.
To do this, run the following command: 

```conda env create -f env2.yml```

## Repository folders

This repository is broken up into several directories and subdirectories. Please
see each directory for information regarding each file. 


### **`notebooks`** 

This is where the tutorials live. Moreover, there is a `.py` file with helper functions used in the notebooks.

### **`datasets`** 

All of the data is stored here. The datasets contain what you'll need to run the
tutorials and/or explore the results from our paper.

## License. 

All the code the notebooks is released under an MIT License shown below: 

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
