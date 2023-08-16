# android-exercicio
Mario Ohashi da Trindade

        var button1 : Button = findViewById(R.id.btnLogin)
        button1.setOnClickListener {
            Toast.makeText(context: this, text:"Clicou no botão", Toast.LENGHT_LONG).show()
        }
        var checkBox: CheckBox = findViewById(R.id.cbTerms)
        val marcado: Boolean = checkBox.isChecked
        var imagemPrincipal: ImageView = findViewById(R.id.imageView)

        if (marcado)
            imagemPrincipal.setImageResource(R.drawable.img1)
        else
            imagemPrincipal.setImageResource(R.drawable.img2)
    }
