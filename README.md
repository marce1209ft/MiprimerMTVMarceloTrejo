def mostrarMiFamilia(request):
return render(request, "ejemplo/saludar.html",
              {"familiar1" : "Marcelo", "Trejo", "12/09/1978"}, 
              "familiar2" : "Delfina", "Trejo", "09/10/2015"},
              "familiar3" : "Eva", "Muñoz", "08/10/1945"},
              "familiar4" : "Ruben", "Trejo", "23/08/1950"},)
              <p style= "color:red"> MALA NOTA = {{n}}<p/> 
      {% else %} <p style= "color:red"> BUENA NOTA = {{n}}<p/>
      {% endif %}
      
      {% endfor %}
 <br/>     
 <br>     
      {% for 1 in familiar1 %}
          <p> {{1}} <p/>
      {% endfor %}
      
      {% for c in familiar2 %}
          <p> {{c}} <p/>
      {% endfor %}
      
      {% for s in familiar3 %}
          <p> {{s}} <p/>
      {% endfor %}
      
      {% for m in familiar4 %}
          <p> {{m}} <p/>
      {% endfor %}
