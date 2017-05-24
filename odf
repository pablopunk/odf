#!/bin/bash

if [ $# -eq 1 ]; then
	editor=$1
else
	editor=echo
fi

git status --porcelain | sed s/^...// | xargs $editor
