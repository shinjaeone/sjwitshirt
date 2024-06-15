  # 각 리스트 요소에 대해 'mouseover'와 'mouseout' 이벤트 리스너를 추가
        listItems.forEach(function(item) {
            item.addEventListener('mouseover', function() {
            this.classList.add('on');
            });
            item.addEventListener('mouseout', function() {
            this.classList.remove('on');
            });
        });
