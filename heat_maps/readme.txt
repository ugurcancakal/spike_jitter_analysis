The names of the files indicates the y axis

dir | rename-item -NewName {$_.name -replace "Synchrony Between Neurons in the region pair_",""}
