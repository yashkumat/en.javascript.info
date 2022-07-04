function multiplyNumeric(obj){
  for(var keys in obj){
    if(typeof obj[keys] === 'number'){
      obj[keys] = obj[keys]*2
    }
  }
}
