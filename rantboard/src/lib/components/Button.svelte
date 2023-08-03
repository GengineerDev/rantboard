<button>
    <slot/>
</button>

<style>
    button {
        background-color: var(--blue);
        padding: 10px 17px;
        border-radius: 4px;
        color: #FFFFFE;
        font-size: 18px;
        font-weight: 700;
        font-family: 'Plus Jakarta Sans', 'Times New Roman', Times, serif;
        border: none;
        cursor: pointer;
    }

    button:hover{
        background-color: #001858;
        transition: 0.4s;
    }
</style>