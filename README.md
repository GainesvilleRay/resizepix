# resizepix
Project to allow a CLAS department to resize photos in batches

# steps

Script to resize images:

environment - import Pillow (current version at 9.5.0)

ask user do they want to resize as a percentage or fixed horizontal size

based on answer, collect number as integer (set limit such as <100% or <1000 pixels)

ask user if they want to update caption or photo credit as .csv

if yes, ask name of file with that information

function to resize images based on percentage

function to resize images based on fixed horizontal size

function to insert ITPC tags from .csv file into .jpg file

make list of filenames of images in directory

for-loop of files through appropriate function(s)

return some sort of confirmation to user
