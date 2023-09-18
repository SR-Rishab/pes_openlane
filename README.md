# Advanced physical design using Openlane/Sky130

# Table of contents

1. [Day 1-Inception of open-source EDA,Openlane and Sky130 PDK](#day-1)
1. [Day 2-Good floorplan vs bad floorplan and introduction to library cells](#day-2)
1. [Day 3-Design library cell using magic layout and ngspice charecterization](#day-3)
1. [Day 4-Pre-layout timing analysis and importance of good clock rate](#day-4)
1. [Day 5-Final steps for RTL2GDS using tritonRoute and openSTA](#day-5)

# Day 1
## Getting familiar with Open source EDA tools
### Design Preparation Step

![day-1-1](https://github.com/SR-Rishab/pes_openlane/assets/107171044/47151e90-a58d-4726-8cd7-6d17e9313b74)

![day-1-2](https://github.com/SR-Rishab/pes_openlane/assets/107171044/31d15a1c-9af1-4492-a548-eda6e5b3d9df)

![day-1-3](https://github.com/SR-Rishab/pes_openlane/assets/107171044/285bbb58-8bd5-48d2-85ca-ce28c8e47f3f)
# Day 2



## Chip Floor Planning Considerations
![day-2-1](https://github.com/SR-Rishab/pes_openlane/assets/107171044/5fb84f01-408d-4d9e-a9c4-a92ec7804fd9)

![day-2-2](https://github.com/SR-Rishab/pes_openlane/assets/107171044/6e9cc54f-6ef9-4d85-8d23-69c616305892)

![day-2-3](https://github.com/SR-Rishab/pes_openlane/assets/107171044/c50d5cb7-bf7b-429a-83b0-b8b60017c4bc)
## Library Binding and Placement
**Netlist Binding and Initial Place Design**

![day-2-4](https://github.com/SR-Rishab/pes_openlane/assets/107171044/39b41136-b085-474f-b0be-6ebf86b7f002)

**Viewing the Placement**
![day-2-5](https://github.com/SR-Rishab/pes_openlane/assets/107171044/0c169701-4c5e-4014-b420-2defccce4033)

# Day 3
## Inception of Layout and CMOS Fabrication Process

**Sky130 Basic Layers Layout and LEF using Inverter**

![day-3-1](https://github.com/SR-Rishab/pes_openlane/assets/107171044/77208b1b-0dce-4ddc-a520-31a25bc908bb)

![day-3-2](https://github.com/SR-Rishab/pes_openlane/assets/107171044/dbad9f51-2895-4d0f-8603-42cc6d6b238f)

**Create Final SPICE Deck**

![day-3-3](https://github.com/SR-Rishab/pes_openlane/assets/107171044/b33d9f2e-b573-4c5c-9126-00f722ac4ebc)

**Characterize Inverter using Sky130 Models**

![day-3-4](https://github.com/SR-Rishab/pes_openlane/assets/107171044/3cf3a53c-9656-48ba-a526-b962207fcac2)

![day-3-7](https://github.com/SR-Rishab/pes_openlane/assets/107171044/bbf31cbe-0718-4db4-af12-c29c999af72c)

![day-3-8](https://github.com/SR-Rishab/pes_openlane/assets/107171044/75d72fe5-4d03-448d-9be7-db1c4977127e)

![day-3-9](https://github.com/SR-Rishab/pes_openlane/assets/107171044/4aa191c2-11e3-483f-a8cc-8c6715c82252)
**Fixing DRC Errors**
![day-3-10](https://github.com/SR-Rishab/pes_openlane/assets/107171044/c782a0fb-2ea0-428f-8be8-04a997fd322b)

![day-3-11](https://github.com/SR-Rishab/pes_openlane/assets/107171044/27364f2c-c65a-4b5e-9660-5ed25ecde8cf)

![day-3-12](https://github.com/SR-Rishab/pes_openlane/assets/107171044/e5c2e138-53f1-4327-99e2-b39edc1951b3)

![day-3-13](https://github.com/SR-Rishab/pes_openlane/assets/107171044/ed39b235-2d08-44cb-bf3f-5b85fd67d3b3)

![day-3-14](https://github.com/SR-Rishab/pes_openlane/assets/107171044/6853ba4b-2953-46d4-b7e7-6a845b3dc571)

# Day 4

## Timing Modelling using Delay Tables

![day-4-1](https://github.com/SR-Rishab/pes_openlane/assets/107171044/88edb039-70dd-4cac-b8d8-2de9910ea677)

![day-4-2](https://github.com/SR-Rishab/pes_openlane/assets/107171044/7aba116b-2eda-4133-abbb-f2122525bc97)

![day-4-3](https://github.com/SR-Rishab/pes_openlane/assets/107171044/e1ba15dc-defb-4f87-ba68-c4d7e766382f)

![day-4-4](https://github.com/SR-Rishab/pes_openlane/assets/107171044/e6a5c5df-fb62-4ddc-928b-a365028e7b2e)

![day-4-5](https://github.com/SR-Rishab/pes_openlane/assets/107171044/0cc146b7-47de-4b5b-b4c5-5683676a51a7)

![day-4-6](https://github.com/SR-Rishab/pes_openlane/assets/107171044/54053e42-8952-41f2-acaf-9bf78845c950)

![day-4-7](https://github.com/SR-Rishab/pes_openlane/assets/107171044/4622073c-1c0b-41fb-ba02-3ba11108c24b)

![day-4-8](https://github.com/SR-Rishab/pes_openlane/assets/107171044/f7084897-521a-4efb-9a97-9b156240c714)

![day-4-9](https://github.com/SR-Rishab/pes_openlane/assets/107171044/01965819-f0be-4b98-99fe-b6704ff8cf8f)

![day-4-10](https://github.com/SR-Rishab/pes_openlane/assets/107171044/8bb87d0b-41bc-485c-94cd-01ae535bd6eb)

**Convert Magic Layout to Standard Cell LEF**
## Timing Analysis with Ideal Clocks using OpenSTA


![day-4-11](https://github.com/SR-Rishab/pes_openlane/assets/107171044/71ff075f-7c6f-4ed5-9dba-8d92766d5ff4)

![day-4-12](https://github.com/SR-Rishab/pes_openlane/assets/107171044/03225b59-28d1-4143-8f6f-a202c8cc0466)

![day-4-13](https://github.com/SR-Rishab/pes_openlane/assets/107171044/b5871c32-641e-4bdc-9a1c-b9ce065da1c8)

![day-4-14](https://github.com/SR-Rishab/pes_openlane/assets/107171044/c559911a-1569-4689-9848-6c87a7b36125)
# Day 5
## Power Distribution Network and Routing
