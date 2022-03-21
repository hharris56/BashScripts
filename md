#!/bin/bash

# Hunter Harris
# 20 March 2022

# single bash command that creates a new
# directory and then navigates into it
# NOTE: must run with 'source md <dirname>'

[ ! -d $1 ] && mkdir $1 && cd $1
