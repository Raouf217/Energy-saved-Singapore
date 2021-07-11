# Energy-saved-Singapore


- Did you know that recycling saves energy by reducing or eliminating the need to make materials from scratch? For example, aluminum can manufacturers can skip the energy-costly process of producing aluminum from ore by cleaning and melting recycled cans. Aluminum is classified as a non-ferrous metal.

- Singapore has an ambitious goal of becoming a zero-waste nation. The amount of waste disposed of in Singapore has increased seven-fold over the last 40 years. At this rate, Semakau Landfill, Singapore's  only landfill, will run out of space by 2035. Making matters worse, Singapore has limited land for building new incineration plants or landfills.

- The government would like to motivate citizens by sharing the total energy that the combined recycling efforts have saved every year. They have asked you to help them.

- There are  three available datasets. The data come from different teams, so the names of waste types may differ.

## Datasets 

### Wastestats.csv

<html>
<div style="background-color: #efebe4; color: #05192d; text-align:left; vertical-align: middle; padding: 15px 25px 15px 25px; line-height: 1.6;"><div style="font-size:16px"><b>datasets/wastestats.csv - Recycling statistics per waste type for the period 2003 to 2017</b></div><div>Source: <a href="https://www.nea.gov.sg/our-services/waste-management/waste-statistics-and-overall-recycling">Singapore National Environment Agency</a></div><ul><li><b>waste_type: </b>The type of waste recycled.</li><li><b>waste_disposed_of_tonne: </b>The amount of waste that could not be recycled (in metric tonnes).</li>    <li><b>total_waste_recycle_tonne: </b>The amount of waste that could be recycled (in metric tonnes).</li><li><b>total_waste_generated: </b>The total amount of waste collected before recycling (in metric tonnes).</li>    <li><b>recycling_rate: </b>The amount of waste recycled per tonne of waste generated.</li><li><b>year: </b>The recycling year.</li></ul> </div><h3>2018_2019_Waste.csv</h3><div style="background-color: #efebe4; color: #05192d; text-align:left; vertical-align: middle; padding: 15px 25px 15px 25px; line-height: 1.6; margin-top: 17px;"><div style="font-size:16px"><b>datasets/2018_2019_waste.csv - Recycling statistics per waste type for the period 2018 to 2019</b></div> <div> Source: <a href="https://www.nea.gov.sg/our-services/waste-management/waste-statistics-and-overall-recycling">Singapore National Environment Agency</a></div><ul><li><b>Waste Type: </b>The type of waste recycled.</li><li><b>Total Generated: </b>The total amount of waste collected before recycling (in thousands of metric tonnes).</li> <li><b>Total Recycled: </b>The amount of waste that could be recycled. (in thousands of metric tonnes).</li><li><b>Year: </b>The recycling year.</li></ul></div><h3>Energy_Saved.csv</h3><div style="background-color: #efebe4; color: #05192d; text-align:left; vertical-align: middle; padding: 15px 25px 15px 25px; line-height: 1.6; margin-top: 17px;"><div style="font-size:16px"><b>datasets/energy_saved.csv -  Estimations of the amount of energy saved per waste type in kWh</b>    </div><ul> <li><b>material: </b>The type of waste recycled.</li><li><b>energy_saved: </b>An estimate of the energy saved (in kiloWatt hour) by recycling a metric tonne of waste.</li>  <li><b>crude_oil_saved: </b>An estimate of the number of barrels of oil saved by recycling a metric tonne of waste.</li></ul></div></html>

## The Results

### After processing the results saved in:

`annual_energy_savings`

### Result

Year  | total_energy_saved (Kwh)
------------- | -------------
2015  |  2579950400
2016  |  1686770400
2017 |  299614000
2018 |  2461129238
2019 |  2551554100
