#!/bin/bash
#
# Move all downloaded files into generic folders based on their document type.

# Change directory to make the following statements cleaner
cd ~/Downloads


if [[ -d ~/Documents ]]; then
  mv *.pdf ~/Documents 2>/dev/null
else
  echo "Documents directory does not exist."
fi

if [[ -d ~/Videos ]]; then
  mv *.webm *.mkv *.mp4 ~/Videos 2>/dev/null
else
  echo "Videos directory does not exist."
fi

if [[ -d ~/Images ]]; then
  mv *.jpg *.jpeg *.png ~/Images 2>/dev/null
else
  echo "Images directory does not exist."
fi
