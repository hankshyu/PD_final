# A Rectilinear Floorplanner

## Usage:
For Ryan Lin:
1. Download boost_1_84_0.tar and place under lib/ folder
2. Extract the archive 
```tar -xvf boost_1_84_0.tar```
3. compile by make
4. strip the binary
```strip ./bin/rfrun```
5. run executable
```
./bin/rfrun -i ./inputs/case02-input.txt  -c ./configs/case02Best.config -o ./outputs/case02-output.txt -d outputs/case02-draw.txt
./bin/rfrun -i ./inputs/case09-input.txt  -c ./configs/case09Best.config -o ./outputs/case09-output.txt -d outputs/case09-draw.txt
./bin/rfrun -i ./inputs/case10-input.txt  -c ./configs/case10Best.config -o ./outputs/case10-output.txt -d outputs/case10-draw.txt
```
6. render the result
``` 
python3 utils/draw_iccad.py ./inputs/case02-input.txt ./outputs/case02-draw.txt ./outputs/case02.png
python3 utils/draw_iccad.py ./inputs/case09-input.txt ./outputs/case09-draw.txt ./outputs/case09.png
python3 utils/draw_iccad.py ./inputs/case10-input.txt ./outputs/case10-draw.txt ./outputs/case10.png
```
7. Done !!

