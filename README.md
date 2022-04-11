<!---Document version 1.0 --->

# CLIpasswordMaker

Applicazione command line per la generazione di password casuali

## Installation 

```
git clone https://github.com/Giuto01/CLIpasswordMaker.git
cd CLIpasswordMaker
sudo sh install.sh
```
## Usage 

Per passowrd di lunghezza arbitraria

```
psw -l <num> 
```

or 

```
psw --lenght <num>
```

Per generare un numero definito di password in una volta

```
psw -n <num>
```
or 

```
psw --number <num>
```

Per maggiori dettagli

```
psw --help
```

## Example 

```
psw --lenght 16 -n 4

Output: TV2£nOFhFlEXH7T#
Output: 8M9DjA0?wVAAR#K8
Output: CSNCrnQle&TnnB1J
Output: %FB£v!NB51Z%N9Mp
```