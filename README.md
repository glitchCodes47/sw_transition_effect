# sw_transition_effect

𝗧𝗿𝗮𝗻𝘀𝗶𝘁𝗶𝗼𝗻 𝗠𝗮𝗻𝗮𝗴𝗲𝗿:
MoreBlock
ActivityTranition (view:view)string(transitionName (intent:intent)

Copy Code :

_view.setTransitionName(_transitionName);

android.app.ActivityOptions optionsCompat = android.app.ActivityOptions.makeSceneTransitionAnimation(YourActivity.this, _view, _transitionName);
        startActivity(_intent, optionsCompat.toBundle());

𝗦𝗲𝘁 𝗧𝗿𝗮𝗻𝘀𝗶𝘁𝗶𝗼𝗻 𝗡𝗮𝗺𝗲:
MoreBlock
setTransitionName (view:view)string(transitionName)

Copy Code :

_view.setTransitionName(_transitionName);
