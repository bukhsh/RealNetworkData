# Network Data for Real World Electricty Transmission Systems

This archive provides power systems test data. The data is obtained from open source material available on world wide web. Reference to the source is given on the webpage of each data set and also in the headers of data files.

## Citing this Archive

If you are using this archive for your research then please cite the following reference:
```
Waqquas Bukhsh, Ken McKinnon, Network data of real transmission networks, April 2013.
```

## Disclaimer

Contents of this archieve are for research and educational purposes. We have made every effort to ensure its accuracy and correctness. However the material in this archieve is distributed with no gurantees regarding correctness, its quality or fitness for a specific application.


# Data Format

This test archive consists of following things:

##   Power Flow Test Cases

The test cases are in MATPOWER[1] case format. MATPOWER is a free open source package of MATLAB® M-files for solving power flow (PF) and optimal power flow(OPF) problems. A free copy of MATPOWER can be downloaded on this link. Since MATPOWER is MATLAB® based so a copy of MATLAB® would be required to use this package. For more information on data format of MATPOWER test cases, click here.

##    Dynamic data for Time Domain Simulation of Power Systems

  The test cases are in PSAT[2] case format. PSAT is a free open source package of MATLAB® M-files for solving power flow (PF), optimal power flow(OPF), continuation power flow (CPF) and time domain simulation (TDS). A free copy of PSAT can be downloaded on this link.
 
 ## Test Cases Diagrams

    The diagrams are in PDF format and are made using a graphing package yEd. 

References
[1] R. D. Zimmerman, C. E. Murillo-Sanchez, and R. J. Thomas, "MATPOWER: Steady-State Operations, Planning and Analysis Tools for Power Systems Research and Education," Power Systems, IEEE Transactions on, vol. 26, no. 1, pp. 12–19, Feb. 2011. [2] F. Milano, L. Vanfretti, J. C. Morataya, An Open Source Power System Virtual Laboratory: The PSAT Case and Experience, IEEE Transactions on Education, Vol. 51, No. 1, pp. 17-23, February 2008. 

# How to use this archive

## Whats in it
Following are the test cases which you can find in this archive:

### 39 Bus Case

This data set is derived from the data available in [1]. There are 10 different kinds of generators in this data set. However the data in [1] assumes same cost for all these generators. We have obtained more plausible cost coefficients from [2], which makes this data more realistic OPF data.

### Iceland Network
This data represents the transmission network data of iceland. It consists of 189 nodes, 35 generators and 206 branches. The power flow data is derived from PSAT file which includes dynamics. The PSAT data was provided by Dr. Patrick McNabb, Durham University.

### Reduced GB Network
  A reduced representative model of Great Britain (GB) transmission network. This model is developed at University of Strathclyde. The data consists of 29 nodes, 66 generators and 99 branches. This data was provided by Manolis Belivanis, University of Strathclyde.

### GB Network

Complete GB transmission data obtained from open source data available from National Grid website. This data consists of 2224 nodes, 394 generators and 3207 branches.

### European Network
  Anonymoused europena transmission network. This data consists of 21097 nodes, 2769 generators and 32112 branches. This data was provided by Richard Lincoln in PSS-E format.

## Running power flow test cases

Download the test case 'test' in your MATPOWER[1] folder. PF and OPF can be run by the commands runpf('test'), runopf('test',) respectively. We have checked the feasibility of all test cases by Matpower and by range of solvers using our AMPL ACOPF model.

 
## References
[1] R. D. Zimmerman, C. E. Murillo-Sanchez, and R. J. Thomas, "MATPOWER: Steady-State Operations, Planning and Analysis Tools for Power Systems Research and Education," Power Systems, IEEE Transactions on, vol. 26, no. 1, pp. 12–19, Feb. 2011. 

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Contributing

We encourage you to submit data sets of power systems to this archive. All submission will be credited.

We are interested in acquiring power systems data for our research purposes. Data files representing network topology, system dynamics, wind data, load and generation data etc are all welcomed. Submissions will be screened and cross checked before they are placed on this archive. There is no restriction on the data format. We shall do data processing to make your data cohernt with the data format of this archive. Please make sure that your submission does not include copyrighted or propritary material.

Send your submissions to wbukhsh[at]gmail.com with 'Submission' in the subject. 



## Authors

* **Waqquas Bukhsh** 
* **Ken McKinnon** 


## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Manolis Belivanis, Keith Bell of University of Strathclyde for provided reduced GB network data.
* Patrick McNabb of Durham University for providing dynamic data of Iceland transmission data.


