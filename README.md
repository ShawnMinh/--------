


Object  ---->  function 

reactive(Object) -----> effect(function) 
数据 变为响应式数据      触发函数

track and trigger
使用类似于 发布订阅模式, 收集依赖, 在适当时机进行触发

class emitter(){
  constructor{
    task
  }
  on(){}
  emit(){}
}

原始数据 对象 数据  -- 建立关系 --  function
