## 리액트 시작하기

const [show,setShow]=useState(false);
- useState :함수형 컴포넌트에서도 상태(state) 관리를 할 수 있게 해 주는 Hook 
- const [변수명, 상태를 업데이트 할 함수명] = useState(초기값) 
		show, setShow

// useEffect :컴포넌트가 렌더링될 때마다 어떠한 작업을 수행하도록 해야 한다면, 그것을 설정하는 Hook으로 사용



<!-- // import React, { useState } from 'react'

// const Footer = () => {
// 	// const [count, setcount] = useState(10)
// 	return (
// 		// <div>
// 		// 	<p>you clicked {count } times </p>
// 		// 	<button onClick={()=>(setcount(count+1))}>click me +</button>
// 		// 	<button onClick={()=>(setcount(count-1))}>click me -</button>
// 		// </div>
// 	)
// }

// export default Footer -->