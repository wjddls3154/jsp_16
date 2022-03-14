# jsp_16 : 버튼 눌렀을 때 변화를 주는

![image](https://user-images.githubusercontent.com/37132897/158134325-c91ff61b-b21a-42fb-91d4-542fe13ac474.png)
- 버튼을 누르기 전 모습

![image](https://user-images.githubusercontent.com/37132897/158134275-efffcce1-8948-40a0-ad83-5079d67aef43.png)
- 버튼을 누른 후 모습

      function f() { // 버튼 눌렀을 때 실행되는
    
      document.getElementById('one').innerHTML = '반갑습니다 !!';  // 출력문이 변경되고,
    
      document.getElementById('one').style.backgroundColor = 'red'; // 배경색이 빨강색이 된다.
      
      }

- 이때, 'one' 은 h1의 id이고, 버튼의 onclick에 f()를 넣었다. 
