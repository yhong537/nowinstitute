
## 슬라이더 

Featured는 

	{{#if featured}}
	{{/if}}

으로 부러올 수 있다.

Featured post를 사용하는 것은 적합하지 않다. 일단 선택된 포스트는 항상 맨 위로 올라가고, 커스텀으로 부른다 해도 최대 블로그 포스트 수(PPP)를 넘어가는 것을 잘린다. 

따라서 Tag를 사용하는 것이 최선의 방법이다. 



***

Tag가 달린 포스트는 다음으로 불러올 수 있다.

    {{#foreach posts}}
      {{#has tag="slider"}}

      {{/has}}
    {{/foreach}}
    
    
  하지만 이 역시 PPP를 넘어가는 것은 불러오지 않는다.   
  