<template>
    <!-- HTML 태그 내용 -->
    <!-- 화면에 표시할 요소들을 정의하는 영역 -->
    <div>
        <span>
            <button>{{ message }}</button>
        </span>
    </div>
</template>
<script>
    export default {
    // 자바스크립트 내용
        data : {
            message : 'click this button'
        }
    }
</script>
<style>
    /* template에 추가한 html 태그의 css 스타일을 정의하는 영역*/
    span {
        font-size : 1.2em;
    }
</style>