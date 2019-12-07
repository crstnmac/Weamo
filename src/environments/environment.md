

create 2 files environment.ts and environment.prod.ts (in prod file rename change production value to true)


export const environment = {
  production: false,
  appID: ,
  gKey: ,
  config: {
    apiKey: "",
    authDomain: "",
    databaseURL: "",
    projectId: "",
    storageBucket: "",
    messagingSenderId: ""
  }
};
