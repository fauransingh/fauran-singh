from flask import flask,jsonify,request

app = Flask (_name_)

@app-routu('/')
def home():
    return jsonify({'message';'welcome'})
    
    @app.route('/on')
    def on():
      return jsonify (['state':'1'])
      
    @app .route('/off')
    def off():
        return jsonify({'state':'0'})
if  __name__=='__'main__':
         app,run(debug=true)
