# rust-pangenome-tools
 - writing all pangenome tools in rust. 
 - This part summarizes all the pangenome alignments. 
 - estimates and gives all descriptive statistics on the pangenome alignment. 
 - general note: Incase of Golang and RUST, please see the last commit message and if it says compiled binary then it is completed or else still in development version.
 ```
 cargo build
 
 ```

 ```
 λ gauravsablok rust-pangenome-tools → λ git main* → ./rust-pangenome-tools -h
 Usage: rust-pangenome-tools <PAFALIGNMENT>

 Arguments:
  <PAFALIGNMENT>  please provide the path to the alignment file

 Options:
  -h, --help     Print help
  -V, --version  Print version

 ```
 - to run the binary

 ```
 λ fedora rust-pangenome-tools → λ git main* → ./target/debug/rust-pangenome-tools ./sample-files/sample.paf
 The total reference aligned sum for the pangenome is 126794249
 The total reference portion of the aligned query is 127158955
 The mode for the reference pangenome alignment is: 612532
 The mode for the query pangenome alignment is 614294
 The pangenome statistics analyzer: The paf analyzer has finished and all the pangenome alignment statistics are given below:
 ```

 Gaurav Sablok
