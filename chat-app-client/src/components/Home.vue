<template>
    <div class="centered-form">
        <div class="centered-form__form">
            <form action="/chat">
                <div class="form-field">
                    <h3>Join a Chat</h3>
                </div>
                <div class="form-field">
                    <label>Display name</label>
                    <input type="text" name="name" autofocus>
                </div>
                <div class="form-field">
                    <label>Room name</label>
                    <input type="text" name="room">
                </div>
                <div class="form-field">
                    <button>Join</button>
                </div>
            </form>
        </div>
    </div>
</template>