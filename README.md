<?php
function fizzBuzz($number){
  if($number % 15 === 0){
    return "Fizz Buzz";
  }elseif($number % 3 === 0){
    return "Fizz";
  }elseif($number % 5 === 0){
    return "Buzz";
  }else{
    return $number;
  }
}

// テスト用の数字を用意
for($i = 1; $i <= 100; $i++){
  echo fizzBuzz($i)."\n";
}
?>
