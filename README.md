# css 문법

## css의 클래스 정의및 사용
    
클래스 정의
    //App.css
    
    .my-style {
      color: blue;
    }
js에서 사용
    //App.js
    
    import './App.css'
    
    function App(){
      return(
      <div className="my-style"> hello </div>
      );
    }
