PADDY DATASET - DATA DESCRIPTION
================================

Dataset:
Paddy Dataset, UCI Machine Learning Repository

คำอธิบายโดยย่อ:
ชุดข้อมูลเกี่ยวกับการเพาะปลูกข้าว ประกอบด้วยข้อมูลพื้นที่และแปลงปลูก พันธุ์ข้าว
ประเภทดิน การเตรียมดิน การใช้ปุ๋ยและสารควบคุมศัตรูพืช รวมถึงข้อมูลสภาพอากาศ
เช่น ฝน อุณหภูมิ ความเร็วลม ทิศทางลม และความชื้นสัมพัทธ์ ตลอดจนผลผลิตข้าว

Data Characteristics:
- Data format: Tabular
- Number of instances: UCI ระบุ 2,790 instances
- Number of features/columns: 45
- Missing values: No
- Supported tasks: Classification, Regression, Clustering
- License: CC BY 4.0

Suggested Target:
- Classification: Variety
- Regression: Paddy yield(in Kg)

Download / Source:
https://archive.ics.uci.edu/dataset/1186/paddy%2Bdataset
DOI: https://doi.org/10.24432/C55W3J


FEATURE TABLE
=============

No.	Feature Name	Type	ความหมาย
1	Hectares	Numerical (Integer)	ขนาดพื้นที่เพาะปลูก หน่วยเฮกตาร์
2	Agriblock	Categorical	เขต/บล็อกการเกษตรที่แปลงตั้งอยู่
3	Variety	Categorical	พันธุ์ข้าวที่ปลูก เช่น CO_43, ponmani, delux ponni
4	Soil Types	Categorical	ประเภทดินของแปลง เช่น alluvial หรือ clay
5	Seedrate(in Kg)	Numerical (Integer)	ปริมาณเมล็ดพันธุ์ที่ใช้ปลูก หน่วยกิโลกรัม
6	LP_Mainfield(in Tonnes)	Numerical (Continuous)	ปริมาณวัสดุ/ปุ๋ยคอกที่ใช้ในการเตรียมดินของแปลงหลัก หน่วยตัน; เอกสารไม่ได้ระบุชนิดวัสดุละเอียด
7	Nursery	Categorical	ประเภทแปลงเพาะกล้า/วิธีเตรียม nursery เช่น dry หรือ wet
8	Nursery area (Cents)	Numerical (Integer)	ขนาดพื้นที่ nursery หน่วย cent
9	LP_nurseryarea(in Tonnes)	Numerical (Integer)	ปริมาณ manure ที่ใช้เตรียมดินบริเวณ nursery หน่วยตัน
10	DAP_20days	Numerical (Integer)	ปริมาณปุ๋ย DAP ที่ใช้ในช่วงประมาณ 20 วันแรก
11	Weed28D_thiobencarb	Numerical	ปริมาณสารกำจัดวัชพืช thiobencarb ที่ใช้ประมาณวันที่ 28
12	Urea_40Days	Numerical (Continuous)	ปริมาณปุ๋ยยูเรียที่ใช้ประมาณวันที่ 40
13	Potassh_50Days	Numerical (Continuous)	ปริมาณปุ๋ย potash/โพแทสเซียมที่ใช้ประมาณวันที่ 50
14	Micronutrients_70Days	Numerical	ปริมาณธาตุอาหารเสริม (micronutrients) ที่ใช้ประมาณวันที่ 70
15	Pest_60Day(in ml)	Numerical	ปริมาณสารควบคุมศัตรูพืชที่ใช้ประมาณวันที่ 60 หน่วยมิลลิลิตร
16	30DRain( in mm)	Numerical (Continuous)	ปริมาณฝนในช่วงประมาณ 30 วันแรก หน่วยมิลลิเมตร
17	30DAI(in mm)	Numerical (Continuous)	ค่าตัวแปร AI ในช่วงประมาณ 30 วันแรก หน่วยมิลลิเมตร; แหล่งข้อมูลไม่ได้อธิบายความหมายของ AI ชัดเจน
18	30_50DRain( in mm)	Numerical (Continuous)	ปริมาณฝนในช่วงประมาณวันที่ 30-50 หน่วยมิลลิเมตร
19	30_50DAI(in mm)	Numerical (Continuous)	ค่าตัวแปร AI ในช่วงประมาณวันที่ 30-50 หน่วยมิลลิเมตร; แหล่งข้อมูลไม่ได้อธิบาย AI ชัดเจน
20	51_70DRain(in mm)	Numerical (Continuous)	ปริมาณฝนในช่วงวันที่ 51-70 หน่วยมิลลิเมตร
21	51_70AI(in mm)	Numerical (Continuous)	ค่าตัวแปร AI ในช่วงวันที่ 51-70 หน่วยมิลลิเมตร; แหล่งข้อมูลไม่ได้อธิบาย AI ชัดเจน
22	71_105DRain(in mm)	Numerical (Continuous)	ปริมาณฝนในช่วงวันที่ 71-105 หน่วยมิลลิเมตร
23	71_105DAI(in mm)	Numerical (Continuous)	ค่าตัวแปร AI ในช่วงวันที่ 71-105 หน่วยมิลลิเมตร; แหล่งข้อมูลไม่ได้อธิบาย AI ชัดเจน
24	Min temp_D1_D30	Numerical (Continuous)	อุณหภูมิต่ำสุดในช่วงวันที่ 1-30
25	Max temp_D1_D30	Numerical (Continuous)	อุณหภูมิสูงสุดในช่วงวันที่ 1-30
26	Min temp_D31_D60	Numerical (Continuous)	อุณหภูมิต่ำสุดในช่วงวันที่ 31-60
27	Max temp_D31_D60	Numerical (Continuous)	อุณหภูมิสูงสุดในช่วงวันที่ 31-60
28	Min temp_D61_D90	Numerical (Continuous)	อุณหภูมิต่ำสุดในช่วงวันที่ 61-90
29	Max temp_D61_D90	Numerical (Continuous)	อุณหภูมิสูงสุดในช่วงวันที่ 61-90
30	Min temp_D91_D120	Numerical (Continuous)	อุณหภูมิต่ำสุดในช่วงวันที่ 91-120
31	Max temp_D91_D120	Numerical (Continuous)	อุณหภูมิสูงสุดในช่วงวันที่ 91-120
32	Inst Wind Speed_D1_D30(in Knots)	Numerical	ความเร็วลมที่บันทึกในช่วงวันที่ 1-30 หน่วย knots
33	Inst Wind Speed_D31_D60(in Knots)	Numerical	ความเร็วลมที่บันทึกในช่วงวันที่ 31-60 หน่วย knots
34	Inst Wind Speed_D61_D90(in Knots)	Numerical	ความเร็วลมที่บันทึกในช่วงวันที่ 61-90 หน่วย knots
35	Inst Wind Speed_D91_D120(in Knots)	Numerical	ความเร็วลมที่บันทึกในช่วงวันที่ 91-120 หน่วย knots
36	Wind Direction_D1_D30	Categorical	ทิศทางลมในช่วงวันที่ 1-30 เช่น SW, NW, ENE, W
37	Wind Direction_D31_D60	Categorical	ทิศทางลมในช่วงวันที่ 31-60
38	Wind Direction_D61_D90	Categorical	ทิศทางลมในช่วงวันที่ 61-90
39	Wind Direction_D91_D120	Categorical	ทิศทางลมในช่วงวันที่ 91-120
40	Relative Humidity_D1_D30	Numerical (Continuous)	ความชื้นสัมพัทธ์ในช่วงวันที่ 1-30
41	Relative Humidity_D31_D60	Numerical (Continuous)	ความชื้นสัมพัทธ์ในช่วงวันที่ 31-60
42	Relative Humidity_D61_D90	Numerical (Continuous)	ความชื้นสัมพัทธ์ในช่วงวันที่ 61-90
43	Relative Humidity_D91_D120	Numerical (Continuous)	ความชื้นสัมพัทธ์ในช่วงวันที่ 91-120
44	Trash(in bundles)	Numerical (Integer)	ปริมาณตัวแปรที่ชุดข้อมูลเรียกว่า Trash วัดเป็นจำนวน bundles; เอกสารไม่ได้อธิบายชนิดวัสดุ/ส่วนของพืชชัดเจน
45	Paddy yield(in Kg)	Numerical (Integer)	ผลผลิตข้าวรวม หน่วยกิโลกรัม
