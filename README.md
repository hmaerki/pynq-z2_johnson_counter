# pynq-z2_johnson_counter
Applied https://community.element14.com/technologies/fpga-group/b/blog/posts/add-pynq-z2-board-to-vivado

See also: https://www.youtube.com/watch?v=UBsCNPWudww

## To rebuild

`$ vivado johnson_counter.xpr`

`Vivado: 'Run Synthesis'`

`Vivado: 'Run Implementation'`

`$ ./run_cp_artifacts.sh`


```
==> Result
johnson_counter.bit
johnson_counter.hwh
johnson_counter.json
ps7_summary.html
```
