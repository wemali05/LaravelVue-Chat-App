<template>
    <div class="col-md-8">
        <div class="card">
            <div class="card-header">Chats</div>
            <div class="card-body">
              <chat-form-component></chat-form-component>
              <chat-messages-component></chat-messages-component>   
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            
        }
    }
</script>

<style>
    .form {
        padding: 8px;
    }
    .form-input {
        width: 100%;
        border: 1px solid #d3e0e9;
        padding: 5px 10px;
        outline: none;
    }
    .notice {
        color: #aaa
    }
      .user {
        font-weight: 800;
    }
    .body {
        margin-bottom: 0;
        white-space: pre-wrap;
    }
    .message {
        border-bottom: 1px solid #000000
    }
    .self {
        background-color: #f0f0f0;
        padding: 10px;
    }
    
    
</style>