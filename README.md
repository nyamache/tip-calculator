# tip-calculator
tipcalculator project #codecademy Javascript projects
const tipCalculator = (quality,total) =>{
if(quality==='bad'){
  return 0.05*total;
}else if(quality==='ok'){
  return 0.15*total;
}else if(quality==='good'){
  return 0.20*total;
}else if(quality==='excellent'){
  return 0.30*total;
}else{
  return 0.18*total;
}
};
