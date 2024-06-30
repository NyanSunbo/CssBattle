# CSS Battle Daily Target - 2024/06/24

[Link to problem](https://cssbattle.dev/play/fQLj0ZRJsJD5jsCq7XLA)

![target](https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_jQJ1dB1.png?alt=media)

```
<div>
    <p></p>
    <dl></dl>
</div>
<dl class="b"></dl>
<p class="bp"></p>
  
 
<style>
*{
  margin: 0px;
  background-color: #EDAF38;
  div{
    display:grid;
    grid-template-columns: 40% 60%;
  }
  p{
  width: 30px;
  height: 140px;
  background: #FFFFCD;
  margin-bottom: 20px;
  box-shadow: 60px 0px #FFFFCD;
  grid-column-start: 0/2;
  }
  dl{
    width: 240px;
    height: 30px;
    background: #FFFFCD;
    box-shadow: 0px 60px #FFFFCD;
  }
  .b{
    transform: translate(0px, 50px);
  }
  .bp{
    transform: translate(310px, -30px);
  }
}
</style>
```