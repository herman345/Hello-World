var min = function(list){  list.sort();    return list[0];   };
var max = function(list){  list.sort();  list.reverse();    return list[0];  };
console.log(max([1, 2, 98, 5, 6, 7, 2, 3,9,8,1,2,97,8,99,51,4,2,6]))
