(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var l;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function da(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var ea=da(this);function n(a,b){if(b)a:{var c=ea;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
n("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.i=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.i};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
n("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=ea[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return fa(aa(this))}})}return a});
function fa(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function p(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function ha(a){if(!(a instanceof Array)){a=p(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ia(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var la="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ia(d,e)&&(a[e]=d[e])}return a};
n("Object.assign",function(a){return a||la});
var na="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},oa=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=na(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),pa;
if("function"==typeof Object.setPrototypeOf)pa=Object.setPrototypeOf;else{var qa;a:{var ra={a:!0},sa={};try{sa.__proto__=ra;qa=sa.a;break a}catch(a){}qa=!1}pa=qa?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var ta=pa;
function t(a,b){a.prototype=na(b.prototype);a.prototype.constructor=a;if(ta)ta(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Y=b.prototype}
function ua(){this.B=!1;this.m=null;this.j=void 0;this.i=1;this.o=this.s=0;this.v=this.l=null}
function wa(a){if(a.B)throw new TypeError("Generator is already running");a.B=!0}
ua.prototype.N=function(a){this.j=a};
function xa(a,b){a.l={Qb:b,Wb:!0};a.i=a.s||a.o}
ua.prototype.return=function(a){this.l={return:a};this.i=this.o};
function v(a,b,c){a.i=c;return{value:b}}
ua.prototype.u=function(a){this.i=a};
function ya(a,b,c){a.s=b;void 0!=c&&(a.o=c)}
function za(a,b){a.i=b;a.s=0}
function Aa(a){a.s=0;var b=a.l.Qb;a.l=null;return b}
function Ba(a){a.v=[a.l];a.s=0;a.o=0}
function Ca(a){var b=a.v.splice(0)[0];(b=a.l=a.l||b)?b.Wb?a.i=a.s||a.o:void 0!=b.u&&a.o<b.u?(a.i=b.u,a.l=null):a.i=a.o:a.i=0}
function Da(a){this.i=new ua;this.j=a}
function Ea(a,b){wa(a.i);var c=a.i.m;if(c)return Fa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.i.return);
a.i.return(b);return Ga(a)}
function Fa(a,b,c,d){try{var e=b.call(a.i.m,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.i.B=!1,e;var f=e.value}catch(g){return a.i.m=null,xa(a.i,g),Ga(a)}a.i.m=null;d.call(a.i,f);return Ga(a)}
function Ga(a){for(;a.i.i;)try{var b=a.j(a.i);if(b)return a.i.B=!1,{value:b.value,done:!1}}catch(c){a.i.j=void 0,xa(a.i,c)}a.i.B=!1;if(a.i.l){b=a.i.l;a.i.l=null;if(b.Wb)throw b.Qb;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ha(a){this.next=function(b){wa(a.i);a.i.m?b=Fa(a,a.i.m.next,b,a.i.N):(a.i.N(b),b=Ga(a));return b};
this.throw=function(b){wa(a.i);a.i.m?b=Fa(a,a.i.m["throw"],b,a.i.N):(xa(a.i,b),b=Ga(a));return b};
this.return=function(b){return Ea(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ia(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function x(a){return Ia(new Ha(new Da(a)))}
function Ja(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
n("Reflect",function(a){return a?a:{}});
n("Reflect.construct",function(){return oa});
n("Reflect.setPrototypeOf",function(a){return a?a:ta?function(b,c){try{return ta(b,c),!0}catch(d){return!1}}:null});
n("Promise",function(a){function b(g){this.i=0;this.l=void 0;this.j=[];this.B=!1;var h=this.m();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.i=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.j=function(g){if(null==this.i){this.i=[];var h=this;this.l(function(){h.o()})}this.i.push(g)};
var e=ea.setTimeout;c.prototype.l=function(g){e(g,0)};
c.prototype.o=function(){for(;this.i&&this.i.length;){var g=this.i;this.i=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(m){this.m(m)}}}this.i=null};
c.prototype.m=function(g){this.l(function(){throw g;})};
b.prototype.m=function(){function g(m){return function(q){k||(k=!0,m.call(h,q))}}
var h=this,k=!1;return{resolve:g(this.K),reject:g(this.o)}};
b.prototype.K=function(g){if(g===this)this.o(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.R(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.J(g):this.s(g)}};
b.prototype.J=function(g){var h=void 0;try{h=g.then}catch(k){this.o(k);return}"function"==typeof h?this.T(h,g):this.s(g)};
b.prototype.o=function(g){this.N(2,g)};
b.prototype.s=function(g){this.N(1,g)};
b.prototype.N=function(g,h){if(0!=this.i)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.i);this.i=g;this.l=h;2===this.i&&this.P();this.v()};
b.prototype.P=function(){var g=this;e(function(){if(g.G()){var h=ea.console;"undefined"!==typeof h&&h.error(g.l)}},1)};
b.prototype.G=function(){if(this.B)return!1;var g=ea.CustomEvent,h=ea.Event,k=ea.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=ea.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.l;return k(g)};
b.prototype.v=function(){if(null!=this.j){for(var g=0;g<this.j.length;++g)f.j(this.j[g]);this.j=null}};
var f=new c;b.prototype.R=function(g){var h=this.m();g.Ua(h.resolve,h.reject)};
b.prototype.T=function(g,h){var k=this.m();try{g.call(h,k.resolve,k.reject)}catch(m){k.reject(m)}};
b.prototype.then=function(g,h){function k(w,u){return"function"==typeof w?function(A){try{m(w(A))}catch(E){q(E)}}:u}
var m,q,r=new b(function(w,u){m=w;q=u});
this.Ua(k(g,m),k(h,q));return r};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Ua=function(g,h){function k(){switch(m.i){case 1:g(m.l);break;case 2:h(m.l);break;default:throw Error("Unexpected state: "+m.i);}}
var m=this;null==this.j?f.j(k):this.j.push(k);this.B=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var m=p(g),q=m.next();!q.done;q=m.next())d(q.value).Ua(h,k)})};
b.all=function(g){var h=p(g),k=h.next();return k.done?d([]):new b(function(m,q){function r(A){return function(E){w[A]=E;u--;0==u&&m(w)}}
var w=[],u=0;do w.push(void 0),u++,d(k.value).Ua(r(w.length-1),q),k=h.next();while(!k.done)})};
return b});
n("WeakMap",function(a){function b(k){this.i=(h+=Math.random()+1).toString();if(k){k=p(k);for(var m;!(m=k.next()).done;)m=m.value,this.set(m[0],m[1])}}
function c(){}
function d(k){var m=typeof k;return"object"===m&&null!==k||"function"===m}
function e(k){if(!ia(k,g)){var m=new c;ba(k,g,{value:m})}}
function f(k){var m=Object[k];m&&(Object[k]=function(q){if(q instanceof c)return q;Object.isExtensible(q)&&e(q);return m(q)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),m=Object.seal({}),q=new a([[k,2],[m,3]]);if(2!=q.get(k)||3!=q.get(m))return!1;q.delete(k);q.set(m,4);return!q.has(k)&&4==q.get(m)}catch(r){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,m){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ia(k,g))throw Error("WeakMap key fail: "+k);k[g][this.i]=m;return this};
b.prototype.get=function(k){return d(k)&&ia(k,g)?k[g][this.i]:void 0};
b.prototype.has=function(k){return d(k)&&ia(k,g)&&ia(k[g],this.i)};
b.prototype.delete=function(k){return d(k)&&ia(k,g)&&ia(k[g],this.i)?delete k[g][this.i]:!1};
return b});
n("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var m=h.i;return fa(function(){if(m){for(;m.head!=h.i;)m=m.previous;for(;m.next!=m.head;)return m=m.next,{done:!1,value:k(m)};m=null}return{done:!0,value:void 0}})}
function d(h,k){var m=k&&typeof k;"object"==m||"function"==m?f.has(k)?m=f.get(k):(m=""+ ++g,f.set(k,m)):m="p_"+k;var q=h.data_[m];if(q&&ia(h.data_,m))for(h=0;h<q.length;h++){var r=q[h];if(k!==k&&r.key!==r.key||k===r.key)return{id:m,list:q,index:h,entry:r}}return{id:m,list:q,index:-1,entry:void 0}}
function e(h){this.data_={};this.i=b();this.size=0;if(h){h=p(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(p([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var m=k.entries(),q=m.next();if(q.done||q.value[0]!=h||"s"!=q.value[1])return!1;q=m.next();return q.done||4!=q.value[0].x||"t"!=q.value[1]||!m.next().done?!1:!0}catch(r){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var m=d(this,h);m.list||(m.list=this.data_[m.id]=[]);m.entry?m.entry.value=k:(m.entry={next:this.i,previous:this.i.previous,head:this.i,key:h,value:k},m.list.push(m.entry),this.i.previous.next=m.entry,this.i.previous=m.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.i=this.i.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var m=this.entries(),q;!(q=m.next()).done;)q=q.value,h.call(k,q[1],q[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ka(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
n("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ka(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
n("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
n("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ka(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
n("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
n("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
n("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
function La(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
n("Array.prototype.entries",function(a){return a?a:function(){return La(this,function(b,c){return[b,c]})}});
n("Array.prototype.keys",function(a){return a?a:function(){return La(this,function(b){return b})}});
n("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
n("Set",function(a){function b(c){this.i=new Map;if(c){c=p(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.i.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(p([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.i.set(c,c);this.size=this.i.size;return this};
b.prototype.delete=function(c){c=this.i.delete(c);this.size=this.i.size;return c};
b.prototype.clear=function(){this.i.clear();this.size=0};
b.prototype.has=function(c){return this.i.has(c)};
b.prototype.entries=function(){return this.i.entries()};
b.prototype.values=function(){return this.i.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.i.forEach(function(f){return c.call(d,f,f,e)})};
return b});
n("Array.prototype.values",function(a){return a?a:function(){return La(this,function(b,c){return c})}});
n("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
n("Object.setPrototypeOf",function(a){return a||ta});
n("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
n("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
n("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ka(this,b,"includes").indexOf(b,c||0)}});
n("globalThis",function(a){return a||ea});
n("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ia(b,d)&&c.push([d,b[d]]);return c}});
n("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ia(b,d)&&c.push(b[d]);return c}});
var Ma=Ma||{},y=this||self;function z(a,b,c){a=a.split(".");c=c||y;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function B(a,b){a=a.split(".");b=b||y;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Na(a){a.sb=void 0;a.getInstance=function(){return a.sb?a.sb:a.sb=new a}}
function Oa(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Pa(a){var b=Oa(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Qa(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Ra(a){return Object.prototype.hasOwnProperty.call(a,Sa)&&a[Sa]||(a[Sa]=++Ta)}
var Sa="closure_uid_"+(1E9*Math.random()>>>0),Ta=0;function Ua(a,b,c){return a.call.apply(a.bind,arguments)}
function Va(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Wa(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Wa=Ua:Wa=Va;return Wa.apply(null,arguments)}
function Ya(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Za(a,b){function c(){}
c.prototype=b.prototype;a.Y=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.sq=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function $a(a){return a}
;function ab(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,ab);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
Za(ab,Error);ab.prototype.name="CustomError";function bb(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.l=!b&&/[?&]ae=1(&|$)/.test(a);this.m=!b&&/[?&]ae=2(&|$)/.test(a);if((this.i=/[?&]adurl=([^&]*)/.exec(a))&&this.i[1]){try{var c=decodeURIComponent(this.i[1])}catch(d){c=null}this.j=c}}
;function cb(){}
function db(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var eb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},fb=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},gb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},hb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},ib=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
fb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d},jb=Array.prototype.every?function(a,b){return Array.prototype.every.call(a,b,void 0)}:function(a,b){for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&!b.call(void 0,d[e],e,a))return!1;
return!0};
function kb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function mb(a,b){b=eb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function nb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Pa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function ob(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function pb(a){var b=qb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function rb(a){for(var b in a)return!1;return!0}
function sb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function tb(a){return null!==a&&"privembed"in a?a.privembed:!1}
function ub(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function vb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function wb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=wb(a[c]);return b}
var xb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function yb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<xb.length;f++)c=xb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var zb;function Ab(){if(void 0===zb){var a=null,b=y.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:$a,createScript:$a,createScriptURL:$a})}catch(c){y.console&&y.console.error(c.message)}zb=a}else zb=a}return zb}
;function Bb(a,b){this.l=a===Cb&&b||""}
Bb.prototype.j=!0;Bb.prototype.i=function(){return this.l};
function Db(a){return new Bb(Cb,a)}
var Cb={};Db("");var Eb={};function Fb(a){this.l=Eb===Eb?a:"";this.j=!0}
Fb.prototype.toString=function(){return this.l.toString()};
Fb.prototype.i=function(){return this.l.toString()};function Gb(a,b){this.l=b===Hb?a:""}
Gb.prototype.toString=function(){return this.l+""};
Gb.prototype.j=!0;Gb.prototype.i=function(){return this.l.toString()};
function Ib(a){if(a instanceof Gb&&a.constructor===Gb)return a.l;Oa(a);return"type_error:TrustedResourceUrl"}
var Hb={};function Lb(a){var b=Ab();a=b?b.createScriptURL(a):a;return new Gb(a,Hb)}
;var Mb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function Nb(a,b){return a<b?-1:a>b?1:0}
;function Ob(a,b){this.l=b===Pb?a:""}
Ob.prototype.toString=function(){return this.l.toString()};
Ob.prototype.j=!0;Ob.prototype.i=function(){return this.l.toString()};
function Qb(a){if(a instanceof Ob&&a.constructor===Ob)return a.l;Oa(a);return"type_error:SafeUrl"}
var Rb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,Pb={},Sb=new Ob("about:invalid#zClosurez",Pb);function Tb(){var a=y.navigator;return a&&(a=a.userAgent)?a:""}
function C(a){return-1!=Tb().indexOf(a)}
;function Ub(){return C("Trident")||C("MSIE")}
function Vb(){return C("Firefox")||C("FxiOS")}
function Wb(){return C("Safari")&&!(Xb()||C("Coast")||C("Opera")||C("Edge")||C("Edg/")||C("OPR")||Vb()||C("Silk")||C("Android"))}
function Xb(){return(C("Chrome")||C("CriOS"))&&!C("Edge")||C("Silk")}
function Yb(){return C("Android")&&!(Xb()||Vb()||C("Opera")||C("Silk"))}
function Zb(a){var b={};a.forEach(function(c){b[c[0]]=c[1]});
return function(c){return b[c.find(function(d){return d in b})]||""}}
function $b(a){var b=Tb();if("Internet Explorer"===a){if(Ub())if((a=/rv: *([\d\.]*)/.exec(b))&&a[1])b=a[1];else{a="";var c=/MSIE +([\d\.]+)/.exec(b);if(c&&c[1])if(b=/Trident\/(\d.\d)/.exec(b),"7.0"==c[1])if(b&&b[1])switch(b[1]){case "4.0":a="8.0";break;case "5.0":a="9.0";break;case "6.0":a="10.0";break;case "7.0":a="11.0"}else a="7.0";else a=c[1];b=a}else b="";return b}var d=RegExp("([A-Z][\\w ]+)/([^\\s]+)\\s*(?:\\((.*?)\\))?","g");c=[];for(var e;e=d.exec(b);)c.push([e[1],e[2],e[3]||void 0]);b=Zb(c);
switch(a){case "Opera":if(C("Opera"))return b(["Version","Opera"]);if(C("OPR"))return b(["OPR"]);break;case "Microsoft Edge":if(C("Edge"))return b(["Edge"]);if(C("Edg/"))return b(["Edg"]);break;case "Chromium":if(Xb())return b(["Chrome","CriOS","HeadlessChrome"])}return"Firefox"===a&&Vb()||"Safari"===a&&Wb()||"Android Browser"===a&&Yb()||"Silk"===a&&C("Silk")?(b=c[2])&&b[1]||"":""}
function ac(a){a=$b(a);if(""===a)return NaN;a=a.split(".");return 0===a.length?NaN:Number(a[0])}
;var bc={};function ec(a){this.l=bc===bc?a:"";this.j=!0}
ec.prototype.i=function(){return this.l.toString()};
ec.prototype.toString=function(){return this.l.toString()};function fc(a,b){b instanceof Ob||b instanceof Ob||(b="object"==typeof b&&b.j?b.i():String(b),Rb.test(b)||(b="about:invalid#zClosurez"),b=new Ob(b,Pb));a.href=Qb(b)}
function gc(a,b){a.rel="stylesheet";a.href=Ib(b).toString();(b=hc('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function ic(){return hc("script[nonce]")}
var jc=/^[\w+/_-]+[=]{0,2}$/;function hc(a,b){b=(b||y).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&jc.test(a)?a:"":""}
;function kc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var lc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function mc(a){return a?decodeURI(a):a}
function nc(a,b){return b.match(lc)[a]||null}
function oc(a){return mc(nc(3,a))}
function pc(a){var b=a.match(lc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function qc(a,b){if(!b)return a;var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;return a[0]+(a[1]?"?"+a[1]:"")+a[2]}
function rc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)rc(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function sc(a,b){var c=[];for(b=b||0;b<a.length;b+=2)rc(a[b],a[b+1],c);return c.join("&")}
function tc(a){var b=[],c;for(c in a)rc(c,a[c],b);return b.join("&")}
function uc(a,b){var c=2==arguments.length?sc(arguments[1],0):sc(arguments,1);return qc(a,c)}
function vc(a,b){b=tc(b);return qc(a,b)}
function wc(a,b,c){c=null!=c?"="+encodeURIComponent(String(c)):"";return qc(a,b+c)}
function xc(a,b,c,d){for(var e=c.length;0<=(b=a.indexOf(c,b))&&b<d;){var f=a.charCodeAt(b-1);if(38==f||63==f)if(f=a.charCodeAt(b+e),!f||61==f||38==f||35==f)return b;b+=e+1}return-1}
var yc=/#|$/,zc=/[?&]($|#)/;function Dc(a,b){for(var c=a.search(yc),d=0,e,f=[];0<=(e=xc(a,d,b,c));)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(zc,"$1")}
;var Ec={};function Fc(a){if(a!==Ec)throw Error("requires a valid immutable API token");}
;function Gc(){return C("iPhone")&&!C("iPod")&&!C("iPad")}
function Hc(){var a=Tb();if(C("Windows")){var b=/Windows (?:NT|Phone) ([0-9.]+)/;b.exec(a)}else Gc()||C("iPad")||C("iPod")?(b=/(?:iPhone|iPod|iPad|CPU)\s+OS\s+(\S+)/,(a=b.exec(a))&&a[1].replace(/_/g,".")):C("Macintosh")?(b=/Mac OS X ([0-9_.]+)/,(a=b.exec(a))&&a[1].replace(/_/g,".")):-1!=Tb().toLowerCase().indexOf("kaios")?(b=/(?:KaiOS)\/(\S+)/i,b.exec(a)):C("Android")?(b=/Android\s+([^\);]+)(\)|;)/,b.exec(a)):C("CrOS")&&(b=/(?:CrOS\s+(?:i686|x86_64)\s+([0-9.]+))/,b.exec(a))}
;function Ic(a){Ic[" "](a);return a}
Ic[" "]=function(){};
function Jc(a){var b=Kc;return Object.prototype.hasOwnProperty.call(b,9)?b[9]:b[9]=a(9)}
;var Lc=C("Opera"),Mc=Ub(),Nc=C("Edge"),Oc=C("Gecko")&&!(-1!=Tb().toLowerCase().indexOf("webkit")&&!C("Edge"))&&!(C("Trident")||C("MSIE"))&&!C("Edge"),Pc=-1!=Tb().toLowerCase().indexOf("webkit")&&!C("Edge"),Qc=C("Android");function Rc(){var a=y.document;return a?a.documentMode:void 0}
var Sc;a:{var Tc="",Uc=function(){var a=Tb();if(Oc)return/rv:([^\);]+)(\)|;)/.exec(a);if(Nc)return/Edge\/([\d\.]+)/.exec(a);if(Mc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(Pc)return/WebKit\/(\S+)/.exec(a);if(Lc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
Uc&&(Tc=Uc?Uc[1]:"");if(Mc){var Vc=Rc();if(null!=Vc&&Vc>parseFloat(Tc)){Sc=String(Vc);break a}}Sc=Tc}var Wc=Sc,Kc={};
function Xc(){return Jc(function(){for(var a=0,b=Mb(String(Wc)).split("."),c=Mb("9").split("."),d=Math.max(b.length,c.length),e=0;0==a&&e<d;e++){var f=b[e]||"",g=c[e]||"";do{f=/(\d*)(\D*)(.*)/.exec(f)||["","","",""];g=/(\d*)(\D*)(.*)/.exec(g)||["","","",""];if(0==f[0].length&&0==g[0].length)break;a=Nb(0==f[1].length?0:parseInt(f[1],10),0==g[1].length?0:parseInt(g[1],10))||Nb(0==f[2].length,0==g[2].length)||Nb(f[2],g[2]);f=f[3];g=g[3]}while(0==a)}return 0<=a})}
var Yc;if(y.document&&Mc){var Zc=Rc();Yc=Zc?Zc:parseInt(Wc,10)||void 0}else Yc=void 0;var $c=Yc;var ad=Gc()||C("iPod"),bd=C("iPad");Yb();Xb();var cd=Wb()&&!(Gc()||C("iPad")||C("iPod"));var dd={},ed=null;
function fd(a,b){Pa(a);void 0===b&&(b=0);if(!ed){ed={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));dd[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===ed[h]&&(ed[h]=g)}}}b=dd[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var k=a[f],m=a[f+1];h=a[f+2];g=b[k>>2];k=b[(k&3)<<4|m>>4];m=b[(m&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+k+m+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var gd="undefined"!==typeof Uint8Array,hd={};var id;function jd(){if(hd!==hd)throw Error("illegal external caller");}
function kd(a){jd();this.ja=a;if(null!=a&&0===a.length)throw Error("ByteString should be constructed with non-empty values");}
kd.prototype.isEmpty=function(){return null==this.ja};var ld="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol(void 0):void 0;function md(a,b){Object.isFrozen(a)||(ld?a[ld]|=b:void 0!==a.ta?a.ta|=b:Object.defineProperties(a,{ta:{value:b,configurable:!0,writable:!0,enumerable:!1}}))}
function nd(a){var b;ld?b=a[ld]:b=a.ta;return null==b?0:b}
function od(a){return Array.isArray(a)?!!(nd(a)&1):!1}
function pd(a){md(a,1);return a}
function qd(a){return Array.isArray(a)?!!(nd(a)&2):!1}
function rd(a){if(!Array.isArray(a))throw Error("cannot mark non-array as immutable");md(a,2)}
function sd(a,b){if(!Array.isArray(a))throw Error("cannot mark non-array as mutable");b?md(a,8):Object.isFrozen(a)||(ld?a[ld]&=-9:void 0!==a.ta&&(a.ta&=-9))}
;function td(a){return qd(a.D)}
function ud(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var vd,Cd=Object.freeze(pd([]));function Dd(a){if(td(a))throw Error("Cannot mutate an immutable Message");}
var Ed="undefined"!=typeof Symbol&&"undefined"!=typeof Symbol.hasInstance;function Fd(a){return{value:a,configurable:!1,writable:!1,enumerable:!1}}
;function Gd(a){return a.displayName||a.name||"unknown type name"}
function Hd(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Gd(b)+" but got "+(a&&Gd(a.constructor)));return a}
function Id(a,b){var c=void 0===c?!1:c;if(Array.isArray(a))return new b(a);if(c)return new b}
;function Jd(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":if(a&&!Array.isArray(a)){if(gd&&null!=a&&a instanceof Uint8Array)return fd(a);if(a instanceof kd){var b=a.ja;null!=b&&"string"!==typeof b&&(gd&&b instanceof Uint8Array?b=fd(b):(Oa(b),b=null));return null==b?"":a.ja=b}}}return a}
;function Kd(a,b){b=void 0===b?Ld:b;return Md(a,b)}
function Nd(a,b){if(null!=a){if(Array.isArray(a))a=Md(a,b);else if(ud(a)){var c={},d;for(d in a)c[d]=Nd(a[d],b);a=c}else a=b(a);return a}}
function Md(a,b){for(var c=a.slice(),d=0;d<c.length;d++)c[d]=Nd(c[d],b);od(a)&&pd(c);return c}
function Od(a){if(a&&"object"==typeof a&&a.toJSON)return a.toJSON();a=Jd(a);return Array.isArray(a)?Kd(a,Od):a}
function Ld(a){return gd&&null!=a&&a instanceof Uint8Array?new Uint8Array(a):a}
;function Pd(a){return a.j||(a.j=a.D[a.l+a.la]={})}
function Qd(a,b,c){return-1===b?null:b>=a.l?a.j?a.j[b]:void 0:(void 0===c?0:c)&&a.j&&(c=a.j[b],null!=c)?c:a.D[b+a.la]}
function D(a,b,c,d,e){d=void 0===d?!1:d;(void 0===e?0:e)||Dd(a);if(b>=a.l||d)return Pd(a)[b]=c,a;void 0!==a.j&&a.l>=a.D.length?(d=a.D.length-1,e=b+a.la,e>=d?(a.D[d]=void 0,a.D[e]=c,a.D.push(a.j)):a.D[e]=c):a.D[b+a.la]=c;void 0!==a.j&&b in a.j&&delete a.j[b];return a}
function Rd(a,b,c,d){c=void 0===c?!0:c;var e=Qd(a,b,d);Array.isArray(e)||(e=Cd);if(td(a))c&&(rd(e),Object.freeze(e));else if(e===Cd||qd(e))e=pd(e.slice()),D(a,b,e,d);return e}
function Sd(a,b,c){a=Qd(a,b);return null==a?c:a}
function Td(a,b,c){null==c?c=Cd:pd(c);return D(a,b,c)}
function Ud(a,b,c,d){Dd(a);(c=Vd(a,c))&&c!==b&&null!=d&&(a.i&&c in a.i&&(a.i[c]=void 0),D(a,c));return D(a,b,d)}
function Vd(a,b){for(var c=0,d=0;d<b.length;d++){var e=b[d];null!=Qd(a,e)&&(0!==c&&D(a,c,void 0,!1,!0),c=e)}return c}
function Wd(a,b,c,d){d=void 0===d?!1:d;var e=d;a.i||(a.i={});var f=a.i[c];if(f)b=f;else if(b=Id(Qd(a,c,e),b))a.i[c]=b,td(a)&&rd(b.D);if(null==b)return b;td(b)&&!td(a)&&(b=b.Bb(),D(a,c,b.D,d),a.i[c]=b);return b}
function Xd(a,b,c,d,e){e=void 0===e?!0:e;a.i||(a.i={});var f=td(a),g=a.i[c];d=Rd(a,c,!0,d);var h=f||qd(d);if(!g){g=[];f=f||h;for(var k=0;k<d.length;k++){var m=d[k];f=f||qd(m);m=Id(m,b);void 0!==m&&(g.push(m),h&&rd(m.D))}a.i[c]=g;sd(d,!f)}b=h||e;e=qd(g);b&&!e&&(Object.isFrozen(g)&&(a.i[c]=g=g.slice()),rd(g),Object.freeze(g));!b&&e&&(a.i[c]=g=g.slice());return g}
function Yd(a,b,c,d){d=void 0===d?!1:d;var e=td(a);b=Xd(a,b,c,d,e);a=Rd(a,c,d);if(!(c=e)&&(c=a)){if(!Array.isArray(a))throw Error("cannot check mutability state of non-array");c=!(nd(a)&8)}if(c){for(c=0;c<b.length;c++)(d=b[c])&&td(d)&&!e&&(b[c]=b[c].Bb(),a[c]=b[c].D);sd(a,!0)}return b}
function G(a,b,c,d){Dd(a);a.i||(a.i={});null==d?b=d=void 0:b=Hd(d,b).D;a.i[c]=d;return D(a,c,b)}
function Zd(a,b,c,d,e){Dd(a);a.i||(a.i={});null!=e?b=Hd(e,b).D:b=e=void 0;a.i[c]=e;Ud(a,c,d,b)}
function $d(a,b,c,d){Dd(a);if(null!=d){var e=pd([]);for(var f=!1,g=0;g<d.length;g++)e[g]=Hd(d[g],b).D,f=f||qd(e[g]);a.i||(a.i={});a.i[c]=d;sd(e,!f)}else a.i&&(a.i[c]=void 0),e=Cd;return D(a,c,e)}
function ae(a,b,c,d){Dd(a);var e=Xd(a,c,b,void 0,!1);c=null!=d?Hd(d,c):new c;a=Rd(a,b);e.push(c);a.push(c.D);Fc(Ec);td(c)&&sd(a,!1)}
;function be(a,b,c){a||(a=ce);ce=null;var d=this.constructor.i||0,e=0<d,f=this.constructor.j;a||(a=f?[f]:[]);e&&0<a.length&&ud(a[a.length-1])&&"g"in a[a.length-1]&&(d=0);this.la=(f?0:-1)-d;this.i=void 0;this.D=a;a:{d=this.D.length;a=d-1;if(d&&(d=this.D[a],ud(d))){this.j=d;b=Object.keys(d);0<b.length&&jb(b,isNaN)?this.l=Number.MAX_VALUE:this.l=a-this.la;break a}void 0!==b&&-1<b?(this.l=Math.max(b,a+1-this.la),this.j=void 0):this.l=Number.MAX_VALUE}if(!e&&this.j&&"g"in this.j)throw Error('Unexpected "g" flag in sparse object of message that is not a group type.');
if(c)for(e=0;e<c.length;e++)b=c[e],b<this.l?(b+=this.la,(a=this.D[b])?Array.isArray(a)&&pd(a):this.D[b]=Cd):(a=Pd(this),(d=a[b])?Array.isArray(d)&&pd(d):a[b]=Cd)}
be.prototype.toJSON=function(){var a=this.D;return vd?a:Kd(a,Od)};
function de(a){vd=!0;try{return JSON.stringify(a.toJSON(),ee)}finally{vd=!1}}
be.prototype.clone=function(){var a=Kd(this.D);ce=a;a=new this.constructor(a);ce=null;fe(a,this);return a};
be.prototype.isMutable=function(a){Fc(a);return!td(this)};
be.prototype.toString=function(){return this.D.toString()};
function ee(a,b){return Jd(b)}
function fe(a,b){b.Ha&&(a.Ha=b.Ha.slice());var c=b.i;if(c){b=b.j;for(var d in c){var e=c[d];if(e){var f=!(!b||!b[d]),g=+d;if(Array.isArray(e)){if(e.length)for(f=Yd(a,e[0].constructor,g,f),g=0;g<Math.min(f.length,e.length);g++)fe(f[g],e[g])}else(f=Wd(a,e.constructor,g,f))&&fe(f,e)}}}}
var ce;function ge(){be.apply(this,arguments)}
t(ge,be);ge.prototype.Bb=function(){return this};
if(Ed){var he={};Object.defineProperties(ge,(he[Symbol.hasInstance]=Fd(function(){throw Error("Cannot perform instanceof checks for MutableMessage");}),he))};function ie(a){var b=this.i,c=this.j;return this.isRepeated?Yd(a,b,c,!0):Wd(a,b,c,!0)}
;function je(a,b,c,d,e,f){(a=a.i&&a.i[c])?Array.isArray(a)?(e=f.kb?pd(a.slice()):a,$d(b,0<e.length?e[0].constructor:void 0,c,e)):G(b,a.constructor,c,a):(gd&&d instanceof Uint8Array?e=d.length?new kd(new Uint8Array(d)):id||(id=new kd(null)):(Array.isArray(d)&&(e?rd(d):od(d)&&f.kb&&(d=d.slice())),e=d),D(b,c,e))}
;function I(){ge.apply(this,arguments)}
t(I,ge);I.prototype.Bb=function(){if(td(this)){var a={kb:!0};var b=td(this);if(b&&!a.kb)throw Error("copyRepeatedFields must be true for frozen messages");var c=new this.constructor;this.Ha&&(c.Ha=this.Ha.slice());for(var d=this.D,e=0;e<d.length;e++){var f=d[e];if(e===d.length-1&&ud(f))for(var g in f){var h=+g;Number.isNaN(h)?Pd(c)[g]=f[g]:je(this,c,h,f[g],b,a)}else je(this,c,e-this.la,f,b,a)}a=c}else a=this;return a};
if(Ed){var ke={};Object.defineProperties(I,(ke[Symbol.hasInstance]=Fd(Object[Symbol.hasInstance]),ke))};function le(a){this.Kb=a}
;function me(a,b,c){this.j=a;this.m=b;this.i=c||[];this.ya=new Map}
l=me.prototype;l.vc=function(a){var b=Ja.apply(1,arguments),c=this.nb(b);c?c.push(new le(a)):this.jc(a,b)};
l.jc=function(a){this.ya.set(this.Rb(Ja.apply(1,arguments)),[new le(a)])};
l.nb=function(){var a=this.Rb(Ja.apply(0,arguments));return this.ya.has(a)?this.ya.get(a):void 0};
l.Ic=function(){var a=this.nb(Ja.apply(0,arguments));return a&&a.length?a[0]:void 0};
l.clear=function(){this.ya.clear()};
l.Rb=function(){var a=Ja.apply(0,arguments);return a?a.join(","):"key"};function ne(a,b){me.call(this,a,3,b)}
t(ne,me);ne.prototype.l=function(a){var b=Ja.apply(1,arguments),c=0,d=this.Ic(b);d&&(c=d.Kb);this.jc(c+a,b)};function oe(a,b){me.call(this,a,2,b)}
t(oe,me);oe.prototype.l=function(a){this.vc(a,Ja.apply(1,arguments))};function pe(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function qe(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Pa(d)?qe.apply(null,d):pe(d)}}
;function J(){this.N=this.N;this.B=this.B}
J.prototype.N=!1;J.prototype.i=function(){return this.N};
J.prototype.dispose=function(){this.N||(this.N=!0,this.C())};
function re(a,b){se(a,Ya(pe,b))}
function se(a,b){a.N?b():(a.B||(a.B=[]),a.B.push(b))}
J.prototype.C=function(){if(this.B)for(;this.B.length;)this.B.shift()()};function te(a,b){this.type=a;this.i=this.target=b;this.defaultPrevented=this.l=!1}
te.prototype.stopPropagation=function(){this.l=!0};
te.prototype.preventDefault=function(){this.defaultPrevented=!0};function ue(a){var b=B("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||y.$googDebugFname||b}catch(g){e="Not available",c=!0}b=ve(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,we[c])c=we[c];else{c=String(c);if(!we[c]){var f=/function\s+([^\(]+)/m.exec(c);we[c]=f?f[1]:"[Anonymous]"}c=we[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function ve(a,b){b||(b={});b[xe(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[xe(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=ve(a,b));return c}
function xe(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var we={};var ye=function(){if(!y.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{y.addEventListener("test",function(){},b),y.removeEventListener("test",function(){},b)}catch(c){}return a}();function ze(a,b){te.call(this,a?a.type:"");this.relatedTarget=this.i=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.j=null;a&&this.init(a,b)}
Za(ze,te);var Ae={2:"touch",3:"pen",4:"mouse"};
ze.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.i=b;if(b=a.relatedTarget){if(Oc){a:{try{Ic(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:Ae[a.pointerType]||"";this.state=a.state;
this.j=a;a.defaultPrevented&&ze.Y.preventDefault.call(this)};
ze.prototype.stopPropagation=function(){ze.Y.stopPropagation.call(this);this.j.stopPropagation?this.j.stopPropagation():this.j.cancelBubble=!0};
ze.prototype.preventDefault=function(){ze.Y.preventDefault.call(this);var a=this.j;a.preventDefault?a.preventDefault():a.returnValue=!1};var Be="closure_listenable_"+(1E6*Math.random()|0);var Ce=0;function De(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.Ya=e;this.key=++Ce;this.Ja=this.Ta=!1}
function Ee(a){a.Ja=!0;a.listener=null;a.proxy=null;a.src=null;a.Ya=null}
;function Ke(a){this.src=a;this.listeners={};this.i=0}
Ke.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.i++);var g=Le(a,b,d,e);-1<g?(b=a[g],c||(b.Ta=!1)):(b=new De(b,this.src,f,!!d,e),b.Ta=c,a.push(b));return b};
Ke.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Le(e,b,c,d);return-1<b?(Ee(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.i--),!0):!1};
function Me(a,b){var c=b.type;c in a.listeners&&mb(a.listeners[c],b)&&(Ee(b),0==a.listeners[c].length&&(delete a.listeners[c],a.i--))}
function Le(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Ja&&f.listener==b&&f.capture==!!c&&f.Ya==d)return e}return-1}
;var Ne="closure_lm_"+(1E6*Math.random()|0),Oe={},Pe=0;function Qe(a,b,c,d,e){if(d&&d.once)Re(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Qe(a,b[f],c,d,e);else c=Se(c),a&&a[Be]?a.aa(b,c,Qa(d)?!!d.capture:!!d,e):Te(a,b,c,!1,d,e)}
function Te(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Qa(e)?!!e.capture:!!e,h=Ue(a);h||(a[Ne]=h=new Ke(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Ve();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)ye||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(We(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Pe++}}
function Ve(){function a(c){return b.call(a.src,a.listener,c)}
var b=Xe;return a}
function Re(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Re(a,b[f],c,d,e);else c=Se(c),a&&a[Be]?a.m.add(String(b),c,!0,Qa(d)?!!d.capture:!!d,e):Te(a,b,c,!0,d,e)}
function Ye(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ye(a,b[f],c,d,e);else(d=Qa(d)?!!d.capture:!!d,c=Se(c),a&&a[Be])?a.m.remove(String(b),c,d,e):a&&(a=Ue(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Le(b,c,d,e)),(c=-1<a?b[a]:null)&&Ze(c))}
function Ze(a){if("number"!==typeof a&&a&&!a.Ja){var b=a.src;if(b&&b[Be])Me(b.m,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(We(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Pe--;(c=Ue(b))?(Me(c,a),0==c.i&&(c.src=null,b[Ne]=null)):Ee(a)}}}
function We(a){return a in Oe?Oe[a]:Oe[a]="on"+a}
function Xe(a,b){if(a.Ja)a=!0;else{b=new ze(b,this);var c=a.listener,d=a.Ya||a.src;a.Ta&&Ze(a);a=c.call(d,b)}return a}
function Ue(a){a=a[Ne];return a instanceof Ke?a:null}
var $e="__closure_events_fn_"+(1E9*Math.random()>>>0);function Se(a){if("function"===typeof a)return a;a[$e]||(a[$e]=function(b){return a.handleEvent(b)});
return a[$e]}
;function af(){J.call(this);this.m=new Ke(this);this.sc=this;this.ka=null}
Za(af,J);af.prototype[Be]=!0;af.prototype.addEventListener=function(a,b,c,d){Qe(this,a,b,c,d)};
af.prototype.removeEventListener=function(a,b,c,d){Ye(this,a,b,c,d)};
function bf(a,b){var c=a.ka;if(c){var d=[];for(var e=1;c;c=c.ka)d.push(c),++e}a=a.sc;c=b.type||b;"string"===typeof b?b=new te(b,a):b instanceof te?b.target=b.target||a:(e=b,b=new te(c,a),yb(b,e));e=!0;if(d)for(var f=d.length-1;!b.l&&0<=f;f--){var g=b.i=d[f];e=cf(g,c,!0,b)&&e}b.l||(g=b.i=a,e=cf(g,c,!0,b)&&e,b.l||(e=cf(g,c,!1,b)&&e));if(d)for(f=0;!b.l&&f<d.length;f++)g=b.i=d[f],e=cf(g,c,!1,b)&&e}
af.prototype.C=function(){af.Y.C.call(this);if(this.m){var a=this.m,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,Ee(d[e]);delete a.listeners[c];a.i--}}this.ka=null};
af.prototype.aa=function(a,b,c,d){return this.m.add(String(a),b,!1,c,d)};
function cf(a,b,c,d){b=a.m.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Ja&&g.capture==c){var h=g.listener,k=g.Ya||g.src;g.Ta&&Me(a.m,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function df(a,b){this.l=a;this.m=b;this.j=0;this.i=null}
df.prototype.get=function(){if(0<this.j){this.j--;var a=this.i;this.i=a.next;a.next=null}else a=this.l();return a};
function ef(a,b){a.m(b);100>a.j&&(a.j++,b.next=a.i,a.i=b)}
;function ff(a,b){return a+Math.random()*(b-a)}
;function gf(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
l=gf.prototype;l.clone=function(){return new gf(this.x,this.y)};
l.equals=function(a){return a instanceof gf&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
l.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
l.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
l.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
l.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function hf(a,b){this.width=a;this.height=b}
l=hf.prototype;l.clone=function(){return new hf(this.width,this.height)};
l.aspectRatio=function(){return this.width/this.height};
l.isEmpty=function(){return!(this.width*this.height)};
l.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
l.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
l.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
l.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function jf(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function kf(a){var b=document;a=String(a);"application/xhtml+xml"===b.contentType&&(a=a.toLowerCase());return b.createElement(a)}
function lf(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var mf;function nf(){var a=y.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!C("Presto")&&(a=function(){var e=kf("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Wa(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!Ub()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.Jb;c.Jb=null;e()}};
return function(e){d.next={Jb:e};d=d.next;b.port2.postMessage(0)}}return function(e){y.setTimeout(e,0)}}
;function of(a){y.setTimeout(function(){throw a;},0)}
;function pf(){this.j=this.i=null}
pf.prototype.add=function(a,b){var c=qf.get();c.set(a,b);this.j?this.j.next=c:this.i=c;this.j=c};
pf.prototype.remove=function(){var a=null;this.i&&(a=this.i,this.i=this.i.next,this.i||(this.j=null),a.next=null);return a};
var qf=new df(function(){return new rf},function(a){return a.reset()});
function rf(){this.next=this.scope=this.i=null}
rf.prototype.set=function(a,b){this.i=a;this.scope=b;this.next=null};
rf.prototype.reset=function(){this.next=this.scope=this.i=null};var sf,tf=!1,uf=new pf;function vf(a,b){sf||wf();tf||(sf(),tf=!0);uf.add(a,b)}
function wf(){if(y.Promise&&y.Promise.resolve){var a=y.Promise.resolve(void 0);sf=function(){a.then(xf)}}else sf=function(){var b=xf;
"function"!==typeof y.setImmediate||y.Window&&y.Window.prototype&&!C("Edge")&&y.Window.prototype.setImmediate==y.setImmediate?(mf||(mf=nf()),mf(b)):y.setImmediate(b)}}
function xf(){for(var a;a=uf.remove();){try{a.i.call(a.scope)}catch(b){of(b)}ef(qf,a)}tf=!1}
;function yf(a){this.i=0;this.B=void 0;this.m=this.j=this.l=null;this.o=this.s=!1;if(a!=cb)try{var b=this;a.call(void 0,function(c){zf(b,2,c)},function(c){zf(b,3,c)})}catch(c){zf(this,3,c)}}
function Af(){this.next=this.context=this.onRejected=this.j=this.i=null;this.l=!1}
Af.prototype.reset=function(){this.context=this.onRejected=this.j=this.i=null;this.l=!1};
var Bf=new df(function(){return new Af},function(a){a.reset()});
function Cf(a,b,c){var d=Bf.get();d.j=a;d.onRejected=b;d.context=c;return d}
function Df(a){return new yf(function(b,c){c(a)})}
yf.prototype.then=function(a,b,c){return Ef(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
yf.prototype.$goog_Thenable=!0;l=yf.prototype;l.gb=function(a,b){return Ef(this,null,a,b)};
l.catch=yf.prototype.gb;l.cancel=function(a){if(0==this.i){var b=new Ff(a);vf(function(){Gf(this,b)},this)}};
function Gf(a,b){if(0==a.i)if(a.l){var c=a.l;if(c.j){for(var d=0,e=null,f=null,g=c.j;g&&(g.l||(d++,g.i==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.i&&1==d?Gf(c,b):(f?(d=f,d.next==c.m&&(c.m=d),d.next=d.next.next):Hf(c),If(c,e,3,b)))}a.l=null}else zf(a,3,b)}
function Jf(a,b){a.j||2!=a.i&&3!=a.i||Kf(a);a.m?a.m.next=b:a.j=b;a.m=b}
function Ef(a,b,c,d){var e=Cf(null,null,null);e.i=new yf(function(f,g){e.j=b?function(h){try{var k=b.call(d,h);f(k)}catch(m){g(m)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof Ff?g(h):f(k)}catch(m){g(m)}}:g});
e.i.l=a;Jf(a,e);return e.i}
l.qd=function(a){this.i=0;zf(this,2,a)};
l.rd=function(a){this.i=0;zf(this,3,a)};
function zf(a,b,c){if(0==a.i){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.i=1;a:{var d=c,e=a.qd,f=a.rd;if(d instanceof yf){Jf(d,Cf(e||cb,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(m){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Qa(d))try{var k=d.then;if("function"===typeof k){Lf(d,k,e,f,a);g=!0;break a}}catch(m){f.call(a,m);g=!0;break a}g=!1}}}g||(a.B=c,a.i=b,a.l=null,Kf(a),3!=b||c instanceof Ff||Mf(a,c))}}
function Lf(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Kf(a){a.s||(a.s=!0,vf(a.Gc,a))}
function Hf(a){var b=null;a.j&&(b=a.j,a.j=b.next,b.next=null);a.j||(a.m=null);return b}
l.Gc=function(){for(var a;a=Hf(this);)If(this,a,this.i,this.B);this.s=!1};
function If(a,b,c,d){if(3==c&&b.onRejected&&!b.l)for(;a&&a.o;a=a.l)a.o=!1;if(b.i)b.i.l=null,Nf(b,c,d);else try{b.l?b.j.call(b.context):Nf(b,c,d)}catch(e){Of.call(null,e)}ef(Bf,b)}
function Nf(a,b,c){2==b?a.j.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function Mf(a,b){a.o=!0;vf(function(){a.o&&Of.call(null,b)})}
var Of=of;function Ff(a){ab.call(this,a)}
Za(Ff,ab);Ff.prototype.name="cancel";function Pf(a,b){af.call(this);this.l=a||1;this.j=b||y;this.o=Wa(this.od,this);this.s=Date.now()}
Za(Pf,af);l=Pf.prototype;l.enabled=!1;l.ca=null;function Qf(a,b){a.l=b;a.ca&&a.enabled?(a.stop(),a.start()):a.ca&&a.stop()}
l.od=function(){if(this.enabled){var a=Date.now()-this.s;0<a&&a<.8*this.l?this.ca=this.j.setTimeout(this.o,this.l-a):(this.ca&&(this.j.clearTimeout(this.ca),this.ca=null),bf(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
l.start=function(){this.enabled=!0;this.ca||(this.ca=this.j.setTimeout(this.o,this.l),this.s=Date.now())};
l.stop=function(){this.enabled=!1;this.ca&&(this.j.clearTimeout(this.ca),this.ca=null)};
l.C=function(){Pf.Y.C.call(this);this.stop();delete this.j};
function Rf(a,b,c){if("function"===typeof a)c&&(a=Wa(a,c));else if(a&&"function"==typeof a.handleEvent)a=Wa(a.handleEvent,a);else throw Error("Invalid listener argument");return 2147483647<Number(b)?-1:y.setTimeout(a,b||0)}
;function Sf(a){this.B=a;this.i=new Map;this.s=new Set;this.l=0;this.m=100;this.flushInterval=3E4;this.j=new Pf(this.flushInterval);this.j.aa("tick",this.ib,!1,this);this.o=!1}
l=Sf.prototype;l.hc=function(a){this.o=a;this.m=1};
function Tf(a){a.j.enabled||a.j.start();a.l++;a.l>=a.m&&a.ib()}
l.ib=function(){var a=this.i.values();a=[].concat(ha(a)).filter(function(b){return b.ya.size});
a.length&&this.B.flush(a,this.o);Uf(a);this.l=0;this.j.enabled&&this.j.stop()};
l.wc=function(a){var b=Ja.apply(1,arguments);this.i.has(a)||this.i.set(a,new ne(a,b))};
l.Hb=function(a){var b=Ja.apply(1,arguments);this.i.has(a)||this.i.set(a,new oe(a,b))};
function Vf(a,b){return a.s.has(b)?void 0:a.i.get(b)}
l.Cb=function(a){this.pc.apply(this,[a,1].concat(ha(Ja.apply(1,arguments))))};
l.pc=function(a,b){var c=Ja.apply(2,arguments),d=Vf(this,a);d&&d instanceof ne&&(d.l(b,c),Tf(this))};
l.hb=function(a,b){var c=Ja.apply(2,arguments),d=Vf(this,a);d&&d instanceof oe&&(d.l(b,c),Tf(this))};
function Uf(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function Wf(a){this.i=a;this.i.Hb("/client_streamz/bg/fil",{mb:3,lb:"rk"})}
function Xf(a){this.i=a;this.i.wc("/client_streamz/bg/fsc",{mb:3,lb:"rk"})}
function Yf(a){this.i=a;this.i.Hb("/client_streamz/bg/fsl",{mb:3,lb:"rk"})}
;function Zf(a){I.call(this,a,-1,$f)}
t(Zf,I);function ag(a){I.call(this,a,-1,bg)}
t(ag,I);function cg(a){I.call(this,a)}
t(cg,I);function dg(a){I.call(this,a)}
t(dg,I);var $f=[3,6,4],bg=[1],eg=[1,2,3],fg=[1,2,3];function gg(a){I.call(this,a,-1,hg)}
t(gg,I);var hg=[1];function ig(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==
c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function jg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;q=m=0}
function b(r){for(var w=g,u=0;64>u;u+=4)w[u/4]=r[u]<<24|r[u+1]<<16|r[u+2]<<8|r[u+3];for(u=16;80>u;u++)r=w[u-3]^w[u-8]^w[u-14]^w[u-16],w[u]=(r<<1|r>>>31)&4294967295;r=e[0];var A=e[1],E=e[2],F=e[3],N=e[4];for(u=0;80>u;u++){if(40>u)if(20>u){var O=F^A&(E^F);var R=1518500249}else O=A^E^F,R=1859775393;else 60>u?(O=A&E|F&(A|E),R=2400959708):(O=A^E^F,R=3395469782);O=((r<<5|r>>>27)&4294967295)+O+N+R+w[u]&4294967295;N=F;F=E;E=(A<<30|A>>>2)&4294967295;A=r;r=O}e[0]=e[0]+r&4294967295;e[1]=e[1]+A&4294967295;e[2]=
e[2]+E&4294967295;e[3]=e[3]+F&4294967295;e[4]=e[4]+N&4294967295}
function c(r,w){if("string"===typeof r){r=unescape(encodeURIComponent(r));for(var u=[],A=0,E=r.length;A<E;++A)u.push(r.charCodeAt(A));r=u}w||(w=r.length);u=0;if(0==m)for(;u+64<w;)b(r.slice(u,u+64)),u+=64,q+=64;for(;u<w;)if(f[m++]=r[u++],q++,64==m)for(m=0,b(f);u+64<w;)b(r.slice(u,u+64)),u+=64,q+=64}
function d(){var r=[],w=8*q;56>m?c(h,56-m):c(h,64-(m-56));for(var u=63;56<=u;u--)f[u]=w&255,w>>>=8;b(f);for(u=w=0;5>u;u++)for(var A=24;0<=A;A-=8)r[w++]=e[u]>>A&255;return r}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var m,q;a();return{reset:a,update:c,digest:d,Cc:function(){for(var r=d(),w="",u=0;u<r.length;u++)w+="0123456789ABCDEF".charAt(Math.floor(r[u]/16))+"0123456789ABCDEF".charAt(r[u]%16);return w}}}
;function kg(a,b,c){var d=String(y.location.href);return d&&a&&b?[b,lg(ig(d),a,c||null)].join(" "):null}
function lg(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],fb(d,function(h){e.push(h)}),mg(e.join(" "));
var f=[],g=[];fb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];fb(d,function(h){e.push(h)});
a=mg(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function mg(a){var b=jg();b.update(a);return b.Cc().toLowerCase()}
;var ng={};function og(a){this.i=a||{cookie:""}}
l=og.prototype;l.isEnabled=function(){if(!y.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{ab:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
l.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Iq;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.ab}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.i.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
l.get=function(a,b){for(var c=a+"=",d=(this.i.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Mb(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
l.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{ab:0,path:b,domain:c});return d};
l.qb=function(){return pg(this).keys};
l.isEmpty=function(){return!this.i.cookie};
l.clear=function(){for(var a=pg(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function pg(a){a=(a.i.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Mb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var qg=new og("undefined"==typeof document?null:document);function rg(a){return!!ng.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function sg(a){a=void 0===a?!1:a;var b=y.__SAPISID||y.__APISID||y.__3PSAPISID||y.__OVERRIDE_SID;rg(a)&&(b=b||y.__1PSAPISID);if(b)return!0;var c=new og(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID");rg(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function tg(a,b,c,d){(a=y[a])||(a=(new og(document)).get(b));return a?kg(a,c,d):null}
function ug(a,b){b=void 0===b?!1:b;var c=ig(String(y.location.href)),d=[];if(sg(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?y.__SAPISID:y.__APISID;e||(e=new og(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?kg(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&rg(b)&&((b=tg("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=tg("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function vg(a){I.call(this,a,-1,wg)}
t(vg,I);var wg=[2];function xg(a){this.i=this.j=this.l=a}
xg.prototype.reset=function(){this.i=this.j=this.l};
xg.prototype.getValue=function(){return this.j};function yg(a){var b=[];zg(new Ag,a,b);return b.join("")}
function Ag(){}
function zg(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),zg(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),Bg(d,c),c.push(":"),zg(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Bg(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Cg={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},Dg=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Bg(a,b){b.push('"',a.replace(Dg,function(c){var d=Cg[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),Cg[c]=d);return d}),'"')}
;function Eg(){}
Eg.prototype.i=null;Eg.prototype.getOptions=function(){var a;(a=this.i)||(a={},Fg(this)&&(a[0]=!0,a[1]=!0),a=this.i=a);return a};var Gg;function Hg(){}
Za(Hg,Eg);function Ig(a){return(a=Fg(a))?new ActiveXObject(a):new XMLHttpRequest}
function Fg(a){if(!a.j&&"undefined"==typeof XMLHttpRequest&&"undefined"!=typeof ActiveXObject){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++){var d=b[c];try{return new ActiveXObject(d),a.j=d}catch(e){}}throw Error("Could not create ActiveXObject. ActiveX might be disabled, or MSXML might not be installed");}return a.j}
Gg=new Hg;function Jg(a){af.call(this);this.headers=new Map;this.K=a||null;this.j=!1;this.J=this.A=null;this.o=this.T="";this.l=this.R=this.v=this.P=!1;this.s=0;this.G=null;this.da="";this.W=this.X=!1}
Za(Jg,af);var Kg=/^https?$/i,Lg=["POST","PUT"],Mg=[];function Ng(a,b,c,d,e,f,g){var h=new Jg;Mg.push(h);b&&h.aa("complete",b);h.m.add("ready",h.Ac,!0,void 0,void 0);f&&(h.s=Math.max(0,f));g&&(h.X=g);h.send(a,c,d,e)}
l=Jg.prototype;l.Ac=function(){this.dispose();mb(Mg,this)};
l.send=function(a,b,c,d){if(this.A)throw Error("[goog.net.XhrIo] Object is active with another request="+this.T+"; newUri="+a);b=b?b.toUpperCase():"GET";this.T=a;this.o="";this.P=!1;this.j=!0;this.A=this.K?Ig(this.K):Ig(Gg);this.J=this.K?this.K.getOptions():Gg.getOptions();this.A.onreadystatechange=Wa(this.Yb,this);try{this.getStatus(),this.R=!0,this.A.open(b,String(a),!0),this.R=!1}catch(g){this.getStatus();Og(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,
d[e]);else if("function"===typeof d.keys&&"function"===typeof d.get){e=p(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=y.FormData&&a instanceof y.FormData;!(0<=eb(Lg,b))||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=p(c);for(d=b.next();!d.done;d=b.next())c=p(d.value),d=c.next().value,c=c.next().value,this.A.setRequestHeader(d,c);this.da&&(this.A.responseType=this.da);"withCredentials"in this.A&&this.A.withCredentials!==this.X&&(this.A.withCredentials=this.X);try{Pg(this),0<this.s&&(this.W=Qg(this.A),this.getStatus(),this.W?(this.A.timeout=this.s,this.A.ontimeout=Wa(this.lc,this)):
this.G=Rf(this.lc,this.s,this)),this.getStatus(),this.v=!0,this.A.send(a),this.v=!1}catch(g){this.getStatus(),Og(this,g)}};
function Qg(a){return Mc&&Xc()&&"number"===typeof a.timeout&&void 0!==a.ontimeout}
l.lc=function(){"undefined"!=typeof Ma&&this.A&&(this.o="Timed out after "+this.s+"ms, aborting",this.getStatus(),bf(this,"timeout"),this.abort(8))};
function Og(a,b){a.j=!1;a.A&&(a.l=!0,a.A.abort(),a.l=!1);a.o=b;Rg(a);Sg(a)}
function Rg(a){a.P||(a.P=!0,bf(a,"complete"),bf(a,"error"))}
l.abort=function(){this.A&&this.j&&(this.getStatus(),this.j=!1,this.l=!0,this.A.abort(),this.l=!1,bf(this,"complete"),bf(this,"abort"),Sg(this))};
l.C=function(){this.A&&(this.j&&(this.j=!1,this.l=!0,this.A.abort(),this.l=!1),Sg(this,!0));Jg.Y.C.call(this)};
l.Yb=function(){this.i()||(this.R||this.v||this.l?Tg(this):this.Rc())};
l.Rc=function(){Tg(this)};
function Tg(a){if(a.j&&"undefined"!=typeof Ma)if(a.J[1]&&4==Wg(a)&&2==a.getStatus())a.getStatus();else if(a.v&&4==Wg(a))Rf(a.Yb,0,a);else if(bf(a,"readystatechange"),a.isComplete()){a.getStatus();a.j=!1;try{if(Xg(a))bf(a,"complete"),bf(a,"success");else{try{var b=2<Wg(a)?a.A.statusText:""}catch(c){b=""}a.o=b+" ["+a.getStatus()+"]";Rg(a)}}finally{Sg(a)}}}
function Sg(a,b){if(a.A){Pg(a);var c=a.A,d=a.J[0]?function(){}:null;
a.A=null;a.J=null;b||bf(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function Pg(a){a.A&&a.W&&(a.A.ontimeout=null);a.G&&(y.clearTimeout(a.G),a.G=null)}
l.isActive=function(){return!!this.A};
l.isComplete=function(){return 4==Wg(this)};
function Xg(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=0===b)a=nc(1,String(a.T)),!a&&y.self&&y.self.location&&(a=y.self.location.protocol.slice(0,-1)),b=!Kg.test(a?a.toLowerCase():"");c=b}return c}
function Wg(a){return a.A?a.A.readyState:0}
l.getStatus=function(){try{return 2<Wg(this)?this.A.status:-1}catch(a){return-1}};
l.getLastError=function(){return"string"===typeof this.o?this.o:String(this.o)};function Yg(a){I.call(this,a)}
t(Yg,I);function Zg(a){I.call(this,a,-1,$g)}
t(Zg,I);var $g=[1];var ah=["platform","platformVersion","architecture","model","uaFullVersion"];new Zg;function bh(a){I.call(this,a)}
t(bh,I);function ch(a){I.call(this,a,31,dh)}
t(ch,I);var dh=[3,20,27];function eh(a){I.call(this,a,17,fh)}
t(eh,I);var fh=[3,5];function gh(a){I.call(this,a,6,hh)}
t(gh,I);var hh=[5];function ih(a){I.call(this,a)}
t(ih,I);var jh;jh=new function(a,b,c){this.j=a;this.fieldName=b;this.i=c;this.isRepeated=0;this.l=ie}(175237375,{zq:0},ih);function kh(a,b,c,d,e,f,g,h,k,m,q){af.call(this);var r=this;this.P="";this.l=[];this.Fb="";this.Gb=this.ra=-1;this.Qa=!1;this.J=this.o=null;this.G=0;this.tc=1;this.timeoutMillis=0;this.da=!1;af.call(this);this.Eb=b||function(){};
this.v=new lh(a,f);this.qc=d;this.Pa=q;this.uc=Ya(ff,0,1);this.T=e||null;this.K=c||null;this.W=g||!1;this.pageId=k||null;this.logger=null;this.withCredentials=!h;this.Ea=f||!1;!this.Ea&&(65<=ac("Chromium")||45<=ac("Firefox")||12<=ac("Safari")||(Gc()||C("iPad")||C("iPod"))&&Hc());a=D(new bh,1,1);mh(this.v,a);this.s=new xg(1E4);this.j=new Pf(this.s.getValue());re(this,this.j);m=nh(this,m);Qe(this.j,"tick",m,!1,this);this.R=new Pf(6E5);re(this,this.R);Qe(this.R,"tick",m,!1,this);this.W||this.R.start();
this.Ea||(Qe(document,"visibilitychange",function(){"hidden"===document.visibilityState&&r.X()}),Qe(document,"pagehide",this.X,!1,this))}
t(kh,af);function nh(a,b){return b?function(){b().then(function(){a.flush()})}:function(){a.flush()}}
kh.prototype.C=function(){this.X();af.prototype.C.call(this)};
function oh(a){a.T||(a.T=.01>a.uc()?"https://www.google.com/log?format=json&hasfast=true":"https://play.google.com/log?format=json&hasfast=true");return a.T}
function ph(a,b){a.s=new xg(1>b?1:b);Qf(a.j,a.s.getValue())}
kh.prototype.log=function(a){a=a.clone();var b=this.tc++;D(a,21,b);this.P&&D(a,26,this.P);if(!Qd(a,1)){b=a;var c=Date.now().toString();D(b,1,c)}null!=Qd(a,15)||D(a,15,60*(new Date).getTimezoneOffset());this.o&&(b=this.o.clone(),G(a,vg,16,b));for(;1E3<=this.l.length;)this.l.shift(),++this.G;this.l.push(a);bf(this,new qh(a));this.W||this.j.enabled||this.j.start()};
kh.prototype.flush=function(a,b){var c=this;if(0===this.l.length)a&&a();else if(this.da)rh(this);else{var d=Date.now();if(this.Gb>d&&this.ra<d)b&&b("throttled");else{var e=sh(this.v,this.l,this.G);d={};var f=this.Eb();f&&(d.Authorization=f);var g=oh(this);this.K&&(d["X-Goog-AuthUser"]=this.K,g=wc(g,"authuser",this.K));this.pageId&&(d["X-Goog-PageId"]=this.pageId,g=wc(g,"pageId",this.pageId));if(f&&this.Fb===f)b&&b("stale-auth-token");else{this.l=[];this.j.enabled&&this.j.stop();this.G=0;var h=de(e),
k;this.J&&this.J.isSupported(h.length)&&(k=this.J.compress(h));var m={url:g,body:h,yc:1,yb:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},q=function(u){c.s.reset();Qf(c.j,c.s.getValue());if(u){var A=null;try{var E=JSON.parse(u.replace(")]}'\n",""));A=new gh(E)}catch(F){}A&&(u=Number(Sd(A,1,"-1")),0<u&&(c.ra=Date.now(),c.Gb=c.ra+u),A=jh.l(A))&&(A=Sd(A,1,-1),-1!=A&&(c.Qa||ph(c,A)))}a&&a()},r=function(u,A){var E=Yd(e,ch,3),F=c.s;
F.i=Math.min(3E5,2*F.i);F.j=Math.min(3E5,F.i+Math.round(.2*(Math.random()-.5)*F.i));Qf(c.j,c.s.getValue());401===u&&f&&(c.Fb=f);void 0===A&&(A=500<=u&&600>u||401===u||0===u);A&&(c.l=E.concat(c.l),c.W||c.j.enabled||c.j.start());b&&b("net-send-failed",u)},w=function(){c.Pa?c.Pa.send(m,q,r):c.qc(m,q,r)};
k?k.then(function(u){m.yb["Content-Encoding"]="gzip";m.yb["Content-Type"]="application/binary";m.body=u;m.yc=2;w()},function(){w()}):w()}}}};
kh.prototype.X=function(){this.flush()};
function rh(a){th(a,function(b,c){b=wc(b,"format","json");b=window.navigator.sendBeacon(b,de(c));a.da&&!b&&(a.da=!1);return b})}
function th(a,b){if(0!==a.l.length){var c=Dc(oh(a),"format");c=uc(c,"auth",a.Eb(),"authuser",a.K||"0");for(var d=0;10>d&&a.l.length;++d){var e=a.l.slice(0,32),f=sh(a.v,e,a.G);if(!b(c,f))break;a.G=0;a.l=a.l.slice(e.length)}a.j.enabled&&a.j.stop()}}
function qh(){te.call(this,"event-logged",void 0)}
t(qh,te);function lh(a,b){this.j=b=void 0===b?!1:b;this.uach=this.locale=null;this.i=new eh;D(this.i,2,a);b||(this.locale=document.documentElement.getAttribute("lang"));mh(this,new bh)}
function mh(a,b){G(a.i,bh,1,b);Qd(b,1)||D(b,1,1);a.j||(b=uh(a),Qd(b,5)||D(b,5,a.locale));a.uach&&(b=uh(a),Wd(b,Zg,9)||G(b,Zg,9,a.uach))}
function vh(a,b){var c=void 0===c?ah:c;b(window,c).then(function(d){a.uach=d;d=uh(a);G(d,Zg,9,a.uach);return!0}).catch(function(){return!1})}
function uh(a){a=Wd(a.i,bh,1);var b=Wd(a,Yg,11);b||(b=new Yg,G(a,Yg,11,b));return b}
function sh(a,b,c){c=void 0===c?0:c;a=a.i.clone();var d=Date.now().toString();a=D(a,4,d);b=$d(a,ch,3,b);c&&D(b,14,c);return b}
;function wh(a,b,c){Ng(a.url,function(d){d=d.target;if(Xg(d)){try{var e=d.A?d.A.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.yb,a.timeoutMillis,a.withCredentials)}
;function xh(){this.l="https://play.google.com/log?format=json&hasfast=true";this.m=!1;this.s=wh;this.i=""}
;function yh(){var a=void 0===a?"":a;var b=void 0===b?!1:b;var c=void 0===c?"":c;var d=new xh;d.i="";""!=a&&(d.l=a);b&&(d.m=!0);c&&(d.j=c);a=new kh(1828,d.J?d.J:ug,"0",d.s,d.l,d.m,!1,d.R,void 0,void 0,d.B?d.B:void 0);d.v&&mh(a.v,d.v);d.j&&(b=d.j,c=uh(a.v),D(c,7,b));d.o&&(a.J=d.o);d.i&&(a.P=d.i);d.N&&((b=d.N)?(a.o||(a.o=new vg),b=de(b),D(a.o,4,b)):a.o&&D(a.o,4,void 0,!1));d.K&&(b=d.K,a.o||(a.o=new vg),Td(a.o,2,b));d.G&&(b=d.G,a.Qa=!0,ph(a,b));d.P&&vh(a.v,d.P);this.i=a}
yh.prototype.flush=function(a){var b=a||[];if(b.length){a=new gg;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=e;var g=new Zf;g=D(g,1,f.j);for(var h=f,k=[],m=0;m<h.i.length;m++)k.push(h.i[m].lb);g=Td(g,3,k);h=[];k=[];m=p(f.ya.keys());for(var q=m.next();!q.done;q=m.next())k.push(q.value.split(","));for(m=0;m<k.length;m++){q=k[m];var r=f.m;for(var w=f.nb(q)||[],u=[],A=0;A<w.length;A++){var E=w[A];E=E&&E.Kb;var F=new dg;switch(r){case 3:Ud(F,1,fg,Number(E));break;case 2:Ud(F,2,fg,Number(E))}u.push(F)}r=
u;for(w=0;w<r.length;w++){u=r[w];A=new ag;u=G(A,dg,2,u);A=q;E=[];F=f;for(var N=[],O=0;O<F.i.length;O++)N.push(F.i[O].mb);F=N;for(N=0;N<F.length;N++){O=F[N];var R=A[N],U=new cg;switch(O){case 3:Ud(U,1,eg,String(R));break;case 2:Ud(U,2,eg,Number(R));break;case 1:Ud(U,3,eg,"true"==R)}E.push(U)}$d(u,cg,1,E);h.push(u)}}$d(g,ag,4,h);c.push(g);e.clear()}$d(a,Zf,1,c);b=this.i;a instanceof ch?b.log(a):(c=new ch,a=de(a),a=D(c,8,a),b.log(a));this.i.flush()}};function zh(){this.o=Ah();this.transport=new yh;this.i=new Sf(this.transport);this.m=new Wf(this.i);this.j=new Xf(this.i);this.l=new Yf(this.i);this.Ba=window.document.location.hostname}
function Ah(){var a,b,c;return null!=(c=null==(a=globalThis.performance)?void 0:null==(b=a.now)?void 0:b.call(a))?c:Date.now()}
;function Bh(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function Ch(a){var b=this;this.Wa=!1;if(a.Gq){var c;this.sa=null!=(c=a.sa)?c:new zh}c=a.program;a=a.globalName;var d=new Bh;this.j=d.promise;this.md=p((0,y[a].a)(c,function(e,f){Promise.resolve().then(function(){var g;if(null!=(g=b.sa)){var h=Ah()-g.o;g.m.i.hb("/client_streamz/bg/fil",h,g.Ba)}d.resolve({xc:e,jd:f})})},!0)).next().value;
this.hd=d.promise.then(function(){})}
Ch.prototype.snapshot=function(a){var b=this;if(this.Wa)throw Error("Already disposed");var c=Ah(),d;null!=(d=this.sa)&&d.j.i.Cb("/client_streamz/bg/fsc",d.Ba);return this.j.then(function(e){var f=e.xc;return new Promise(function(g){f(function(h){var k;if(null!=(k=b.sa)){var m=Ah()-c;k.l.i.hb("/client_streamz/bg/fsl",m,k.Ba)}g(h)},[a.Mb,
a.kd])})})};
Ch.prototype.dispose=function(){var a;null!=(a=this.sa)&&a.i.ib();this.Wa=!0;this.j.then(function(b){(b=b.jd)&&b()})};
Ch.prototype.i=function(){return this.Wa};var Dh=window;Db("csi.gstatic.com");Db("googleads.g.doubleclick.net");Db("partner.googleadservices.com");Db("pubads.g.doubleclick.net");Db("securepubads.g.doubleclick.net");Db("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var Eh;try{new URL("s://g"),Eh=!0}catch(a){Eh=!1}var Fh=Eh;function Gh(a,b){a.src=Ib(b);var c,d;(c=(b=null==(d=(c=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:d.call(c,"script[nonce]"))?b.nonce||b.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",c)}
;function Hh(a){var b=Ih;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function Jh(){var a=[];Hh(function(b){a.push(b)});
return a}
var Ih={Ed:"allow-forms",Fd:"allow-modals",Gd:"allow-orientation-lock",Hd:"allow-pointer-lock",Id:"allow-popups",Jd:"allow-popups-to-escape-sandbox",Kd:"allow-presentation",Ld:"allow-same-origin",Md:"allow-scripts",Nd:"allow-top-navigation",Od:"allow-top-navigation-by-user-activation"},Kh=db(function(){return Jh()});
function Lh(){var a=Mh(),b={};fb(Kh(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Mh(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function Nh(a){this.isValid=a}
function Oh(a){return new Nh(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var Ph=[Oh("data"),Oh("http"),Oh("https"),Oh("mailto"),Oh("ftp"),new Nh(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function Qh(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Rh=(new Date).getTime();var Sh="client_dev_domain client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");ha(Sh);function Th(a){af.call(this);var b=this;this.v=this.l=0;this.Z=null!=a?a:{S:function(e,f){return setTimeout(e,f)},
fa:function(e){clearTimeout(e)}};
var c,d;this.j=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.o=function(){return x(function(e){return v(e,Uh(b),0)})};
window.addEventListener("offline",this.o);window.addEventListener("online",this.o);this.v||Vh(this)}
t(Th,af);function Wh(){var a=Xh;Th.i||(Th.i=new Th(a));return Th.i}
Th.prototype.dispose=function(){window.removeEventListener("offline",this.o);window.removeEventListener("online",this.o);this.Z.fa(this.v);delete Th.i};
Th.prototype.L=function(){return this.j};
function Vh(a){a.v=a.Z.S(function(){var b;return x(function(c){if(1==c.i)return a.j?(null==(b=window.navigator)?0:b.onLine)?c.u(3):v(c,Uh(a),3):v(c,Uh(a),3);Vh(a);c.i=0})},3E4)}
function Uh(a,b){return a.s?a.s:a.s=new Promise(function(c){var d,e,f,g;return x(function(h){switch(h.i){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,ya(h,2,3),d&&(a.l=a.Z.S(function(){d.abort()},b||2E4)),v(h,fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:Ba(h);a.s=void 0;a.l&&(a.Z.fa(a.l),a.l=0);g!==a.j&&(a.j=g,a.j?bf(a,"networkstatus-online"):bf(a,"networkstatus-offline"));c(g);Ca(h);break;case 2:Aa(h),g=!1,h.u(3)}})})}
;var Yh={Sh:"EMBEDDED_PLAYER_MODE_UNKNOWN",Ph:"EMBEDDED_PLAYER_MODE_DEFAULT",Rh:"EMBEDDED_PLAYER_MODE_PFP",Qh:"EMBEDDED_PLAYER_MODE_PFL"},Zh={Yp:"WEB_DISPLAY_MODE_UNKNOWN",Up:"WEB_DISPLAY_MODE_BROWSER",Wp:"WEB_DISPLAY_MODE_MINIMAL_UI",Xp:"WEB_DISPLAY_MODE_STANDALONE",Vp:"WEB_DISPLAY_MODE_FULLSCREEN"};function $h(){this.data_=[];this.i=-1}
$h.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data_[a]!==b&&(this.data_[a]=b,this.i=-1)};
$h.prototype.get=function(a){return!!this.data_[a]};
function ai(a){-1===a.i&&(a.i=ib(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.i}
;function bi(a,b){this.i=a[y.Symbol.iterator]();this.j=b}
bi.prototype[Symbol.iterator]=function(){return this};
bi.prototype.next=function(){var a=this.i.next();return{value:a.done?void 0:this.j.call(void 0,a.value),done:a.done}};
function ci(a,b){return new bi(a,b)}
;function di(){this.blockSize=-1}
;function ei(){this.blockSize=-1;this.blockSize=64;this.i=[];this.o=[];this.s=[];this.l=[];this.l[0]=128;for(var a=1;a<this.blockSize;++a)this.l[a]=0;this.m=this.j=0;this.reset()}
Za(ei,di);ei.prototype.reset=function(){this.i[0]=1732584193;this.i[1]=4023233417;this.i[2]=2562383102;this.i[3]=271733878;this.i[4]=3285377520;this.m=this.j=0};
function fi(a,b,c){c||(c=0);var d=a.s;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.i[0];c=a.i[1];var g=a.i[2],h=a.i[3],k=a.i[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var m=1518500249}else f=c^g^h,m=1859775393;else 60>e?(f=c&g|h&(c|g),m=2400959708):
(f=c^g^h,m=3395469782);f=(b<<5|b>>>27)+f+k+m+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.i[0]=a.i[0]+b&4294967295;a.i[1]=a.i[1]+c&4294967295;a.i[2]=a.i[2]+g&4294967295;a.i[3]=a.i[3]+h&4294967295;a.i[4]=a.i[4]+k&4294967295}
ei.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.o,f=this.j;d<b;){if(0==f)for(;d<=c;)fi(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){fi(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){fi(this,e);f=0;break}}this.j=f;this.m+=b}};
ei.prototype.digest=function(){var a=[],b=8*this.m;56>this.j?this.update(this.l,56-this.j):this.update(this.l,this.blockSize-(this.j-56));for(var c=this.blockSize-1;56<=c;c--)this.o[c]=b&255,b/=256;fi(this,this.o);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.i[c]>>d&255,++b;return a};function gi(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function hi(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function ii(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:gi(a).match(/\S+/g)||[],b=0<=eb(a,b));return b}
function ji(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):ii(a,"inverted-hdpi")&&hi(a,Array.prototype.filter.call(a.classList?a.classList:gi(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function ki(){}
ki.prototype.next=function(){return li};
var li={done:!0,value:void 0};function mi(a){return{value:a,done:!1}}
ki.prototype.ea=function(){return this};function ni(a){if(a instanceof oi||a instanceof pi||a instanceof qi)return a;if("function"==typeof a.next)return new oi(function(){return a});
if("function"==typeof a[Symbol.iterator])return new oi(function(){return a[Symbol.iterator]()});
if("function"==typeof a.ea)return new oi(function(){return a.ea()});
throw Error("Not an iterator or iterable.");}
function oi(a){this.j=a}
oi.prototype.ea=function(){return new pi(this.j())};
oi.prototype[Symbol.iterator]=function(){return new qi(this.j())};
oi.prototype.i=function(){return new qi(this.j())};
function pi(a){this.j=a}
t(pi,ki);pi.prototype.next=function(){return this.j.next()};
pi.prototype[Symbol.iterator]=function(){return new qi(this.j)};
pi.prototype.i=function(){return new qi(this.j)};
function qi(a){oi.call(this,function(){return a});
this.l=a}
t(qi,oi);qi.prototype.next=function(){return this.l.next()};function ri(a,b){this.j={};this.i=[];this.oa=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof ri)for(c=a.qb(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
l=ri.prototype;l.qb=function(){si(this);return this.i.concat()};
l.has=function(a){return ti(this.j,a)};
l.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||ui;si(this);for(var c,d=0;c=this.i[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function ui(a,b){return a===b}
l.isEmpty=function(){return 0==this.size};
l.clear=function(){this.j={};this.oa=this.size=this.i.length=0};
l.remove=function(a){return this.delete(a)};
l.delete=function(a){return ti(this.j,a)?(delete this.j[a],--this.size,this.oa++,this.i.length>2*this.size&&si(this),!0):!1};
function si(a){if(a.size!=a.i.length){for(var b=0,c=0;b<a.i.length;){var d=a.i[b];ti(a.j,d)&&(a.i[c++]=d);b++}a.i.length=c}if(a.size!=a.i.length){var e={};for(c=b=0;b<a.i.length;)d=a.i[b],ti(e,d)||(a.i[c++]=d,e[d]=1),b++;a.i.length=c}}
l.get=function(a,b){return ti(this.j,a)?this.j[a]:b};
l.set=function(a,b){ti(this.j,a)||(this.size+=1,this.i.push(a),this.oa++);this.j[a]=b};
l.forEach=function(a,b){for(var c=this.qb(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
l.clone=function(){return new ri(this)};
l.keys=function(){return ni(this.ea(!0)).i()};
l.values=function(){return ni(this.ea(!1)).i()};
l.entries=function(){var a=this;return ci(this.keys(),function(b){return[b,a.get(b)]})};
l.ea=function(a){si(this);var b=0,c=this.oa,d=this,e=new ki;e.next=function(){if(c!=d.oa)throw Error("The map has changed since the iterator was created");if(b>=d.i.length)return li;var f=d.i[b++];return mi(a?f:d.j[f])};
return e};
function ti(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function K(a){J.call(this);this.s=1;this.m=[];this.o=0;this.j=[];this.l={};this.v=!!a}
Za(K,J);l=K.prototype;l.subscribe=function(a,b,c){var d=this.l[a];d||(d=this.l[a]=[]);var e=this.s;this.j[e]=a;this.j[e+1]=b;this.j[e+2]=c;this.s=e+3;d.push(e);return e};
function vi(a,b,c,d){if(b=a.l[b]){var e=a.j;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.Da(b)}}
l.Da=function(a){var b=this.j[a];if(b){var c=this.l[b];0!=this.o?(this.m.push(a),this.j[a+1]=function(){}):(c&&mb(c,a),delete this.j[a],delete this.j[a+1],delete this.j[a+2])}return!!b};
l.qa=function(a,b){var c=this.l[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.v)for(e=0;e<c.length;e++){var g=c[e];wi(this.j[g+1],this.j[g+2],d)}else{this.o++;try{for(e=0,f=c.length;e<f&&!this.i();e++)g=c[e],this.j[g+1].apply(this.j[g+2],d)}finally{if(this.o--,0<this.m.length&&0==this.o)for(;c=this.m.pop();)this.Da(c)}}return 0!=e}return!1};
function wi(a,b,c){vf(function(){a.apply(b,c)})}
l.clear=function(a){if(a){var b=this.l[a];b&&(b.forEach(this.Da,this),delete this.l[a])}else this.j.length=0,this.l={}};
l.C=function(){K.Y.C.call(this);this.clear();this.m.length=0};function xi(a){this.i=a}
xi.prototype.set=function(a,b){void 0===b?this.i.remove(a):this.i.set(a,yg(b))};
xi.prototype.get=function(a){try{var b=this.i.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
xi.prototype.remove=function(a){this.i.remove(a)};function yi(a){this.i=a}
Za(yi,xi);function zi(a){this.data=a}
function Ai(a){return void 0===a||a instanceof zi?a:new zi(a)}
yi.prototype.set=function(a,b){yi.Y.set.call(this,a,Ai(b))};
yi.prototype.j=function(a){a=yi.Y.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
yi.prototype.get=function(a){if(a=this.j(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Bi(a){this.i=a}
Za(Bi,yi);Bi.prototype.set=function(a,b,c){if(b=Ai(b)){if(c){if(c<Date.now()){Bi.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}Bi.Y.set.call(this,a,b)};
Bi.prototype.j=function(a){var b=Bi.Y.j.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())Bi.prototype.remove.call(this,a);else return b}};function Ci(){}
;function Di(){}
Za(Di,Ci);Di.prototype[Symbol.iterator]=function(){return ni(this.ea(!0)).i()};
Di.prototype.clear=function(){var a=Array.from(this);a=p(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function Ei(a){this.i=a}
Za(Ei,Di);l=Ei.prototype;l.isAvailable=function(){if(!this.i)return!1;try{return this.i.setItem("__sak","1"),this.i.removeItem("__sak"),!0}catch(a){return!1}};
l.set=function(a,b){try{this.i.setItem(a,b)}catch(c){if(0==this.i.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
l.get=function(a){a=this.i.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.i.removeItem(a)};
l.ea=function(a){var b=0,c=this.i,d=new ki;d.next=function(){if(b>=c.length)return li;var e=c.key(b++);if(a)return mi(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return mi(e)};
return d};
l.clear=function(){this.i.clear()};
l.key=function(a){return this.i.key(a)};function Fi(){var a=null;try{a=window.localStorage||null}catch(b){}this.i=a}
Za(Fi,Ei);function Gi(a,b){this.j=a;this.i=null;var c;if(c=Mc)c=!(9<=Number($c));if(c){Hi||(Hi=new ri);this.i=Hi.get(a);this.i||(b?this.i=document.getElementById(b):(this.i=document.createElement("userdata"),this.i.addBehavior("#default#userData"),document.body.appendChild(this.i)),Hi.set(a,this.i));try{this.i.load(this.j)}catch(d){this.i=null}}}
Za(Gi,Di);var Ii={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},Hi=null;function Ji(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return Ii[b]})}
l=Gi.prototype;l.isAvailable=function(){return!!this.i};
l.set=function(a,b){this.i.setAttribute(Ji(a),b);Ki(this)};
l.get=function(a){a=this.i.getAttribute(Ji(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.i.removeAttribute(Ji(a));Ki(this)};
l.ea=function(a){var b=0,c=this.i.XMLDocument.documentElement.attributes,d=new ki;d.next=function(){if(b>=c.length)return li;var e=c[b++];if(a)return mi(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return mi(e)};
return d};
l.clear=function(){for(var a=this.i.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);Ki(this)};
function Ki(a){try{a.i.save(a.j)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function Li(a,b){this.j=a;this.i=b+"::"}
Za(Li,Di);Li.prototype.set=function(a,b){this.j.set(this.i+a,b)};
Li.prototype.get=function(a){return this.j.get(this.i+a)};
Li.prototype.remove=function(a){this.j.remove(this.i+a)};
Li.prototype.ea=function(a){var b=this.j[Symbol.iterator](),c=this,d=new ki;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.i.length)!=c.i;){e=b.next();if(e.done)return e;e=e.value}return mi(a?e.slice(c.i.length):c.j.get(e))};
return d};function Mi(a){I.call(this,a)}
t(Mi,I);function Ni(a){I.call(this,a)}
t(Ni,I);Ni.prototype.getKey=function(){return Qd(this,1)};
Ni.prototype.getValue=function(){return Qd(this,2===Vd(this,Oi)?2:-1)};
Ni.prototype.setValue=function(a){return Ud(this,2,Oi,a)};
var Oi=[2,3,4,5,6];function Pi(a){I.call(this,a)}
t(Pi,I);function Qi(a){I.call(this,a)}
t(Qi,I);function Ri(a){I.call(this,a,-1,Si)}
t(Ri,I);var Si=[2];function Ti(a){I.call(this,a,-1,Ui)}
t(Ti,I);Ti.prototype.getPlayerType=function(){return Qd(this,36)};
Ti.prototype.setHomeGroupInfo=function(a){return G(this,Ri,81,a)};
var Ui=[9,66,24,32,86,100,101];function Vi(a){I.call(this,a,-1,Wi)}
t(Vi,I);var Wi=[15,26,28];function Xi(a){I.call(this,a)}
t(Xi,I);Xi.prototype.setToken=function(a){return D(this,2,a)};function Yi(a){I.call(this,a,-1,Zi)}
t(Yi,I);Yi.prototype.setSafetyMode=function(a){return D(this,5,a)};
var Zi=[12];function $i(a){I.call(this,a,-1,aj)}
t($i,I);$i.prototype.s=function(a){G(this,Ti,1,a)};
var aj=[12];function bj(a){this.name=a}
;var cj=new bj("continuationCommand");var dj=new bj("webCommandMetadata");var ej=new bj("signalServiceEndpoint");var fj=new bj("feedbackEndpoint");function gj(a){I.call(this,a,-1,hj)}
t(gj,I);function ij(a){I.call(this,a)}
t(ij,I);ij.prototype.getKey=function(){return Sd(this,1,"")};
ij.prototype.getValue=function(){return Sd(this,2,"")};
ij.prototype.setValue=function(a){return D(this,2,a)};
var hj=[4,5];function jj(a){I.call(this,a)}
t(jj,I);function kj(a){I.call(this,a)}
t(kj,I);var lj=[2,3,4];function mj(a){I.call(this,a)}
t(mj,I);mj.prototype.getMessage=function(){return Sd(this,1,"")};function nj(a){I.call(this,a)}
t(nj,I);function oj(a){I.call(this,a)}
t(oj,I);function pj(a){I.call(this,a,-1,qj)}
t(pj,I);var qj=[10,17];function rj(a){I.call(this,a)}
t(rj,I);function sj(a){I.call(this,a)}
t(sj,I);sj.prototype.V=function(a){D(this,1,a)};function tj(a){I.call(this,a)}
t(tj,I);function uj(a){I.call(this,a)}
t(uj,I);function vj(a){I.call(this,a)}
t(vj,I);function wj(a){I.call(this,a,-1,xj)}
t(wj,I);wj.prototype.getVideoData=function(){return Wd(this,vj,15)};
var xj=[4];function yj(a){I.call(this,a)}
t(yj,I);function zj(a,b){G(a,tj,1,b)}
yj.prototype.V=function(a){D(this,2,a)};
function Aj(a){I.call(this,a)}
t(Aj,I);function Bj(a,b){G(a,tj,1,b)}
;function Cj(a){I.call(this,a,-1,Dj)}
t(Cj,I);Cj.prototype.V=function(a){D(this,1,a)};
function Ej(a,b){G(a,tj,2,b)}
var Dj=[3];function Fj(a){I.call(this,a)}
t(Fj,I);Fj.prototype.V=function(a){D(this,1,a)};function Gj(a){I.call(this,a)}
t(Gj,I);Gj.prototype.V=function(a){D(this,1,a)};function Hj(a){I.call(this,a)}
t(Hj,I);Hj.prototype.V=function(a){D(this,1,a)};function Ij(a){I.call(this,a)}
t(Ij,I);Ij.prototype.V=function(a){D(this,1,a)};function Jj(a){I.call(this,a)}
t(Jj,I);function Kj(a){I.call(this,a)}
t(Kj,I);function Lj(a){I.call(this,a,-1,Mj)}
t(Lj,I);function Nj(a,b){return D(a,1,b)}
Lj.prototype.getPlayerType=function(){return Sd(this,7,0)};
Lj.prototype.setVideoId=function(a){return D(this,19,a)};
function Oj(a,b){return D(a,25,b)}
function Pj(a,b){ae(a,68,Qj,b)}
function Qj(a){I.call(this,a)}
t(Qj,I);Qj.prototype.getId=function(){return Sd(this,2,"")};
var Mj=[83,68];function Rj(a){I.call(this,a)}
t(Rj,I);function Sj(a){I.call(this,a)}
t(Sj,I);function Tj(a){I.call(this,a)}
t(Tj,I);function Uj(a){I.call(this,a,440)}
t(Uj,I);
var Vj=[23,24,11,6,7,5,2,3,13,20,21,22,28,32,37,229,241,45,59,225,288,72,73,78,208,156,202,215,74,76,79,80,111,85,91,97,100,102,105,119,126,127,136,146,148,151,157,158,159,163,164,168,176,222,383,177,178,179,411,184,188,189,190,191,193,194,195,196,197,198,199,200,201,402,320,203,204,205,206,258,259,260,261,327,209,219,226,227,232,233,234,240,244,247,248,249,251,256,257,266,254,255,270,272,278,291,293,300,304,308,309,310,311,313,314,319,321,323,324,328,330,331,332,334,337,338,340,344,348,350,351,352,
353,354,355,356,357,358,361,363,364,368,369,370,373,374,375,378,380,381,388,389,403,410,412,429,413,414,415,416,417,418,430,423,424,425,426,427,431,117,439];var Wj={Ti:0,Ei:1,Ki:2,Li:4,Qi:8,Mi:16,Ni:32,Si:64,Ri:128,Gi:256,Ii:512,Pi:1024,Hi:2048,Ji:4096,Fi:8192,Oi:16384};function qk(a){I.call(this,a)}
t(qk,I);function rk(a){I.call(this,a)}
t(rk,I);rk.prototype.setVideoId=function(a){return Ud(this,1,sk,a)};
rk.prototype.getPlaylistId=function(){return Qd(this,2===Vd(this,sk)?2:-1)};
var sk=[1,2];function tk(a){I.call(this,a,-1,uk)}
t(tk,I);var uk=[3];var vk=new bj("webPlayerShareEntityServiceEndpoint");var wk=new bj("playlistEditEndpoint");var xk=new bj("modifyChannelNotificationPreferenceEndpoint");var yk=new bj("unsubscribeEndpoint");var zk=new bj("subscribeEndpoint");function Ak(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var Bk=y.window,Ck,Dk,Ek=(null==Bk?void 0:null==(Ck=Bk.yt)?void 0:Ck.config_)||(null==Bk?void 0:null==(Dk=Bk.ytcfg)?void 0:Dk.data_)||{};z("yt.config_",Ek);function Fk(){Ak(Ek,arguments)}
function L(a,b){return a in Ek?Ek[a]:b}
function Gk(){var a=Ek.EXPERIMENT_FLAGS;return a?a.web_disable_gel_stp_ecatcher_killswitch:void 0}
;function M(a){a=Hk(a);return"string"===typeof a&&"false"===a?!1:!!a}
function Ik(a,b){a=Hk(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function Jk(){return L("EXPERIMENTS_TOKEN","")}
function Hk(a){var b=L("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:L("EXPERIMENT_FLAGS",{})[a]}
function Kk(){var a=[],b=L("EXPERIMENTS_FORCED_FLAGS",{});for(c in b)a.push({key:c,value:String(b[c])});var c=L("EXPERIMENT_FLAGS",{});for(var d in c)d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var Lk=[];function Mk(a){Lk.forEach(function(b){return b(a)})}
function Nk(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Ok(b)}}:a}
function Ok(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=L("ERRORS",[]),e.push([a,"ERROR",b,c,d]),Fk("ERRORS",e));Mk(a)}
function Pk(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=L("ERRORS",[]),e.push([a,"WARNING",b,c,d]),Fk("ERRORS",e))}
;function Qk(){var a=Rk;B("yt.ads.biscotti.getId_")||z("yt.ads.biscotti.getId_",a)}
function Sk(a){z("yt.ads.biscotti.lastId_",a)}
;var Tk=/^[\w.]*$/,Uk={q:!0,search_query:!0};function Vk(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Wk(f[0]||""),h=Wk(f[1]||"");g in c?Array.isArray(c[g])?nb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(r){var k=r,m=f[0],q=String(Vk);k.args=[{key:m,value:f[1],query:a,method:Xk==q?"unchanged":q}];Uk.hasOwnProperty(m)||Pk(k)}}return c}
var Xk=String(Vk);function Yk(a){var b=[];ob(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];fb(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function Zk(a){"?"==a.charAt(0)&&(a=a.substr(1));return Vk(a,"&")}
function $k(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),Zk(1<a.length?a[1]:a[0])):{}}
function al(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Zk(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return vc(a,e)+d}
function bl(a){if(!b)var b=window.location.href;var c=nc(1,a),d=oc(a);c&&d?(a=a.match(lc),b=b.match(lc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?oc(b)==d&&(Number(nc(4,b))||null)==(Number(nc(4,a))||null):!0;return a}
function Wk(a){return a&&a.match(Tk)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function cl(a){var b=dl;a=void 0===a?B("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Rh;e.flash="0";a:{try{var f=b.i.top.location.href}catch(ma){f=2;break a}f=f?f===b.j.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?Dh:g;try{var h=g.history.length}catch(ma){h=0}e.u_his=h;var k;e.u_h=null==(k=Dh.screen)?void 0:k.height;var m;e.u_w=null==(m=Dh.screen)?void 0:m.width;var q;e.u_ah=null==(q=Dh.screen)?void 0:q.availHeight;var r;e.u_aw=
null==(r=Dh.screen)?void 0:r.availWidth;var w;e.u_cd=null==(w=Dh.screen)?void 0:w.colorDepth}catch(ma){}h=b.i;try{var u=h.screenX;var A=h.screenY}catch(ma){}try{var E=h.outerWidth;var F=h.outerHeight}catch(ma){}try{var N=h.innerWidth;var O=h.innerHeight}catch(ma){}try{var R=h.screenLeft;var U=h.screenTop}catch(ma){}try{N=h.innerWidth,O=h.innerHeight}catch(ma){}try{var ca=h.screen.availWidth;var lb=h.screen.availTop}catch(ma){}u=[R,U,u,A,ca,lb,E,F,N,O];try{var Xa=(b.i.top||window).document,ja="CSS1Compat"==
Xa.compatMode?Xa.documentElement:Xa.body;var H=(new hf(ja.clientWidth,ja.clientHeight)).round()}catch(ma){H=new hf(-12245933,-12245933)}Xa=H;H={};var ka=void 0===ka?y:ka;ja=new $h;ka.SVGElement&&ka.document.createElementNS&&ja.set(0);A=Lh();A["allow-top-navigation-by-user-activation"]&&ja.set(1);A["allow-popups-to-escape-sandbox"]&&ja.set(2);ka.crypto&&ka.crypto.subtle&&ja.set(3);ka.TextDecoder&&ka.TextEncoder&&ja.set(4);ka=ai(ja);H.bc=ka;H.bih=Xa.height;H.biw=Xa.width;H.brdim=u.join();b=b.j;b=(H.vis=
b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,H.wgl=!!Dh.WebGLRenderingContext,H);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var dl=new function(){var a=window.document;this.i=window;this.j=a};
z("yt.ads_.signals_.getAdSignalsString",function(a){return Yk(cl(a))});Date.now();var el="XMLHttpRequest"in y?function(){return new XMLHttpRequest}:null;
function fl(){if(!el)return null;var a=el();return"open"in a?a:null}
function gl(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function hl(a,b){"function"===typeof a&&(a=Nk(a));return window.setTimeout(a,b)}
function il(a){window.clearTimeout(a)}
;var jl={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},kl="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ha(Sh)),ll=!1;
function ml(a,b){b=void 0===b?{}:b;var c=bl(a),d=M("web_ajax_ignore_global_headers_if_set"),e;for(e in jl){var f=L(jl[e]);"X-Goog-Visitor-Id"!==e||f||(f=L("VISITOR_DATA"));!f||!c&&oc(a)||d&&void 0!==b[e]||(b[e]=f)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!oc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!oc(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||
!oc(a))b["X-YouTube-Ad-Signals"]=Yk(cl());return b}
function nl(a){var b=window.location.search,c=oc(a);M("debug_handle_relative_url_for_query_forward_killswitch")||c||!bl(a)||(c=document.location.hostname);var d=mc(nc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Zk(b),f={};fb(kl,function(g){e[g]&&(f[g]=e[g])});
return al(a,f||{},!1)}
function ol(a,b){var c=b.format||"JSON";a=pl(a,b);var d=ql(a,b),e=!1,f=rl(a,function(k){if(!e){e=!0;h&&il(h);var m=gl(k),q=null,r=400<=k.status&&500>k.status,w=500<=k.status&&600>k.status;if(m||r||w)q=sl(a,c,k,b.convertToSafeHtml);if(m)a:if(k&&204==k.status)m=!0;else{switch(c){case "XML":m=0==parseInt(q&&q.return_code,10);break a;case "RAW":m=!0;break a}m=!!q}q=q||{};r=b.context||y;m?b.onSuccess&&b.onSuccess.call(r,k,q):b.onError&&b.onError.call(r,k,q);b.onFinish&&b.onFinish.call(r,k,q)}},b.method,
d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=hl(function(){e||(e=!0,f.abort(),il(h),g.call(b.context||y,f))},d)}return f}
function pl(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=L("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=al(a,b||{},!0);return a}
function ql(a,b){var c=L("XSRF_FIELD_NAME"),d=L("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=L("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||oc(a)&&!b.withCredentials&&oc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=Zk(e),yb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):tc(e));f=e||f&&!rb(f);!ll&&f&&"POST"!=b.method&&(ll=
!0,Ok(Error("AJAX request with postData should use POST")));return e}
function sl(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Pk(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?tl(a):null)e={},fb(a.getElementsByTagName("*"),function(g){e[g.tagName]=ul(g)})}d&&vl(e);
return e}
function vl(a){if(Qa(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;Db("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=a[b],e=Ab();d=e?e.createHTML(d):d;a[c]=new ec(d)}else vl(a[b])}}
function tl(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function ul(a){var b="";fb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function rl(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&Nk(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=fl();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;M("debug_forward_web_query_parameters")&&(a=nl(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=ml(a,e))for(var m in e)k.setRequestHeader(m,e[m]),"content-type"==m.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;function wl(a){var b=this;this.j=void 0;this.i=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.j=c});
a.addEventListener("appinstalled",function(){b.i=!0},{once:!0})}
function xl(){if(!y.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return y.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":y.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":y.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":y.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function yl(a,b,c,d,e){qg.set(""+a,b,{ab:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function zl(){if(!qg.isEnabled())return!1;if(!qg.isEmpty())return!0;qg.set("TESTCOOKIESENABLED","1",{ab:60});if("1"!==qg.get("TESTCOOKIESENABLED"))return!1;qg.remove("TESTCOOKIESENABLED");return!0}
;var Al=B("ytglobal.prefsUserPrefsPrefs_")||{};z("ytglobal.prefsUserPrefsPrefs_",Al);function Bl(){this.i=L("ALT_PREF_COOKIE_NAME","PREF");this.j=L("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=qg.get(""+this.i,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(Al[d]=c.toString())}}}
Bl.prototype.get=function(a,b){Cl(a);Dl(a);a=void 0!==Al[a]?Al[a].toString():null;return null!=a?a:b?b:""};
Bl.prototype.set=function(a,b){Cl(a);Dl(a);if(null==b)throw Error("ExpectedNotNull");Al[a]=b.toString()};
function El(a){return!!((Fl("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
Bl.prototype.remove=function(a){Cl(a);Dl(a);delete Al[a]};
Bl.prototype.clear=function(){for(var a in Al)delete Al[a]};
function Dl(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function Cl(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function Fl(a){a=void 0!==Al[a]?Al[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Na(Bl);var Gl={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},Hl={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_INVALID:31},Il={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},Jl={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function Kl(){var a=y.navigator;return a?a.connection:void 0}
function Ll(){var a=Kl();if(a){var b=Gl[a.type||"unknown"]||"CONN_UNKNOWN";a=Gl[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function Ml(){var a=Kl();if(null!=a&&a.effectiveType)return Jl.hasOwnProperty(a.effectiveType)?Jl[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function Nl(){return"INNERTUBE_API_KEY"in Ek&&"INNERTUBE_API_VERSION"in Ek}
function Ol(){return{innertubeApiKey:L("INNERTUBE_API_KEY"),innertubeApiVersion:L("INNERTUBE_API_VERSION"),rb:L("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),Tb:L("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Kc:L("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:L("INNERTUBE_CONTEXT_CLIENT_VERSION"),Vb:L("INNERTUBE_CONTEXT_HL"),Ub:L("INNERTUBE_CONTEXT_GL"),Lc:L("INNERTUBE_HOST_OVERRIDE")||"",Nc:!!L("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Mc:!!L("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:L("SERIALIZED_CLIENT_CONFIG_DATA")}}
function Pl(a){var b={client:{hl:a.Vb,gl:a.Ub,clientName:a.Tb,clientVersion:a.innertubeContextClientVersion,configInfo:a.rb}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=y.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=Jk();""!==c&&(b.client.experimentsToken=c);c=Kk();0<c.length&&(b.request={internalExperimentFlags:c});Ql(a,void 0,b);Rl(void 0,b);Sl(a,void 0,b);Tl(void 0,b);L("DELEGATED_SESSION_ID")&&!M("pageid_as_header_web")&&(b.user={onBehalfOfUser:L("DELEGATED_SESSION_ID")});
a=Object;c=a.assign;for(var d=b.client,e={},f=p(Object.entries(Zk(L("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=p(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===g?e.browserVersion=h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,e);return b}
function Ul(a){var b=new $i,c=new Ti;D(c,1,a.Vb);D(c,2,a.Ub);D(c,16,a.Kc);D(c,17,a.innertubeContextClientVersion);if(a.rb){var d=a.rb,e=new Pi;d.coldConfigData&&D(e,1,d.coldConfigData);d.appInstallData&&D(e,6,d.appInstallData);d.coldHashData&&D(e,3,d.coldHashData);d.hotHashData&&D(e,5,d.hotHashData);G(c,Pi,62,e)}(d=y.devicePixelRatio)&&1!=d&&D(c,65,d);d=Jk();""!==d&&D(c,54,d);d=Kk();if(0<d.length){e=new Vi;for(var f=0;f<d.length;f++){var g=new Ni;D(g,1,d[f].key);g.setValue(d[f].value);ae(e,15,Ni,
g)}G(b,Vi,5,e)}Ql(a,c);Rl(c);Sl(a,c);Tl(c);L("DELEGATED_SESSION_ID")&&!M("pageid_as_header_web")&&(a=new Yi,D(a,3,L("DELEGATED_SESSION_ID")));a=p(Object.entries(Zk(L("DEVICE",""))));for(d=a.next();!d.done;d=a.next())e=p(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?D(c,12,e):"cmodel"===d?D(c,13,e):"cbr"===d?D(c,87,e):"cbrver"===d?D(c,88,e):"cos"===d?D(c,18,e):"cosver"===d?D(c,19,e):"cplatform"===d&&D(c,42,e);b.s(c);return b}
function Ql(a,b,c){a=a.Tb;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=Wd(b,Qi,96)||new Qi;var d=xl();d=Object.keys(Zh).indexOf(d);d=-1===d?null:d;null!==d&&D(c,3,d);G(b,Qi,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=xl())}
function Rl(a,b){var c;if(M("web_log_memory_total_kbytes")&&(null==(c=y.navigator)?0:c.deviceMemory)){var d;c=null==(d=y.navigator)?void 0:d.deviceMemory;a?D(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function Sl(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=Wd(b,Pi,62))?d:new Pi;D(c,6,a.appInstallData);G(b,Pi,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function Tl(a,b){var c=Ll();c&&(a?D(a,61,Hl[c]):b&&(b.client.connectionType=c));M("web_log_effective_connection_type")&&(c=Ml())&&(a?D(a,94,Il[c]):b&&(b.client.effectiveConnectionType=c))}
function Vl(a,b,c){c=void 0===c?{}:c;var d={};L("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":L("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||L("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.rq||L("AUTHORIZATION"))||(a?b="Bearer "+B("gapi.auth.getToken")().qq:b=ug([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=L("SESSION_INDEX",0),M("pageid_as_header_web")&&(d["X-Goog-PageId"]=L("DELEGATED_SESSION_ID")));return d}
;function Wl(a){a=Object.assign({},a);delete a.Authorization;var b=ug();if(b){var c=new ei;c.update(L("INNERTUBE_API_KEY"));c.update(b);a.hash=fd(c.digest(),3)}return a}
;function Xl(a){var b=new Fi;(b=b.isAvailable()?a?new Li(b,a):b:null)||(a=new Gi(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.i=(a=b)?new Bi(a):null;this.j=document.domain||window.location.hostname}
Xl.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.i)try{this.i.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(yg(b))}catch(f){return}else e=escape(b);yl(a,e,c,this.j)};
Xl.prototype.get=function(a,b){var c=void 0,d=!this.i;if(!d)try{c=this.i.get(a)}catch(e){d=!0}if(d&&(c=qg.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Xl.prototype.remove=function(a){this.i&&this.i.remove(a);var b=this.j;qg.remove(""+a,"/",void 0===b?"youtube.com":b)};var Yl=window,P=Yl.ytcsi&&Yl.ytcsi.now?Yl.ytcsi.now:Yl.performance&&Yl.performance.timing&&Yl.performance.now&&Yl.performance.timing.navigationStart?function(){return Yl.performance.timing.navigationStart+Yl.performance.now()}:function(){return(new Date).getTime()};var Zl;function $l(){Zl||(Zl=new Xl("yt.innertube"));return Zl}
function am(a,b,c,d){if(d)return null;d=$l().get("nextId",!0)||1;var e=$l().get("requests",!0)||{};e[d]={method:a,request:b,authState:Wl(c),requestTime:Math.round(P())};$l().set("nextId",d+1,86400,!0);$l().set("requests",e,86400,!0);return d}
function bm(a){var b=$l().get("requests",!0)||{};delete b[a];$l().set("requests",b,86400,!0)}
function cm(a){var b=$l().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(P())-d.requestTime)){var e=d.authState,f=Wl(Vl(!1));ub(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(P())),dm(a,d.method,e,{}));delete b[c]}}$l().set("requests",b,86400,!0)}}
;function em(){}
em.prototype.S=function(a,b){return fm(a,1,b)};
function gm(a,b){fm(a,2,b)}
function hm(a){var b=B("yt.scheduler.instance.addImmediateJob");b?b(a):a()}
;function im(){em.apply(this,arguments)}
t(im,em);function jm(){im.i||(im.i=new im);return im.i}
function fm(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=B("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):hl(a,c||0)}
im.prototype.fa=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=B("yt.scheduler.instance.cancelJob");b?b(a):il(a)}};
im.prototype.start=function(){var a=B("yt.scheduler.instance.start");a&&a()};
im.prototype.pause=function(){var a=B("yt.scheduler.instance.pause");a&&a()};var Xh=jm();var km=ad||bd;function lm(a){var b=Tb();return b?0<=b.toLowerCase().indexOf(a):!1}
;var mm=function(){var a;return function(){a||(a=new Xl("ytidb"));return a}}();
function nm(){var a;return null==(a=mm())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var om=[],pm,qm=!1;function rm(){var a={};for(pm=new sm(void 0===a.handleError?tm:a.handleError,void 0===a.logEvent?um:a.logEvent);0<om.length;)switch(a=om.shift(),a.type){case "ERROR":pm.handleError(a.payload);break;case "EVENT":pm.logEvent(a.eventType,a.payload)}}
function vm(a){qm||(pm?pm.handleError(a):(om.push({type:"ERROR",payload:a}),10<om.length&&om.shift()))}
function wm(a,b){qm||(pm?pm.logEvent(a,b):(om.push({type:"EVENT",eventType:a,payload:b}),10<om.length&&om.shift()))}
;function Q(a){var b=Ja.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ha(b))}
t(Q,Error);function xm(){try{return ym(),!0}catch(a){return!1}}
function ym(a){if(void 0!==L("DATASYNC_ID"))return L("DATASYNC_ID");throw new Q("Datasync ID not set",void 0===a?"unknown":a);}
;function zm(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function Am(a){return a.substr(0,a.indexOf(":"))||a}
;var Bm={},Cm=(Bm.AUTH_INVALID="No user identifier specified.",Bm.EXPLICIT_ABORT="Transaction was explicitly aborted.",Bm.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Bm.MISSING_INDEX="Index not created.",Bm.MISSING_OBJECT_STORES="Object stores not created.",Bm.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",Bm.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",Bm.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
Bm.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",Bm.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Bm.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",Bm.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",Bm),Dm={},Em=(Dm.AUTH_INVALID="ERROR",Dm.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",Dm.EXPLICIT_ABORT="IGNORED",Dm.IDB_NOT_SUPPORTED="ERROR",Dm.MISSING_INDEX=
"WARNING",Dm.MISSING_OBJECT_STORES="ERROR",Dm.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",Dm.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",Dm.QUOTA_EXCEEDED="WARNING",Dm.QUOTA_MAYBE_EXCEEDED="WARNING",Dm.UNKNOWN_ABORT="WARNING",Dm.INCOMPATIBLE_DB_VERSION="WARNING",Dm),Fm={},Gm=(Fm.AUTH_INVALID=!1,Fm.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Fm.EXPLICIT_ABORT=!1,Fm.IDB_NOT_SUPPORTED=!1,Fm.MISSING_INDEX=!1,Fm.MISSING_OBJECT_STORES=!1,Fm.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Fm.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,Fm.QUOTA_EXCEEDED=!1,Fm.QUOTA_MAYBE_EXCEEDED=!0,Fm.UNKNOWN_ABORT=!0,Fm.INCOMPATIBLE_DB_VERSION=!1,Fm);function Hm(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?Cm[a]:c;d=void 0===d?Em[a]:d;e=void 0===e?Gm[a]:e;Q.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.i=e;Object.setPrototypeOf(this,Hm.prototype)}
t(Hm,Q);function Im(a,b){Hm.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},Cm.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Im.prototype)}
t(Im,Hm);function Jm(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Jm.prototype)}
t(Jm,Error);var Km=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Lm(a,b,c,d){b=Am(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Hm)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new Hm("QUOTA_EXCEEDED",a);if(cd&&"UnknownError"===e.name)return new Hm("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Jm)return new Hm("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&Km.some(function(f){return e.message.includes(f)}))return new Hm("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new Hm("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",Zb:e.name})];e.level="WARNING";return e}
function Mm(a,b,c){var d=nm();return new Hm("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function Nm(a){if(!a)throw Error();throw a;}
function Om(a){return a}
function Pm(a){this.i=a}
function Qm(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=p(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=p(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.i=[];this.onRejected=[];a=a.i;try{a(c,b)}catch(e){b(e)}}
Qm.all=function(a){return new Qm(new Pm(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={xa:0};f.xa<a.length;f={xa:f.xa},++f.xa)Qm.resolve(a[f.xa]).then(function(g){return function(h){d[g.xa]=h;e--;0===e&&b(d)}}(f)).catch(function(g){c(g)})}))};
Qm.resolve=function(a){return new Qm(new Pm(function(b,c){a instanceof Qm?a.then(b,c):b(a)}))};
Qm.reject=function(a){return new Qm(new Pm(function(b,c){c(a)}))};
Qm.prototype.then=function(a,b){var c=this,d=null!=a?a:Om,e=null!=b?b:Nm;return new Qm(new Pm(function(f,g){"PENDING"===c.state.status?(c.i.push(function(){Rm(c,c,d,f,g)}),c.onRejected.push(function(){Sm(c,c,e,f,g)})):"FULFILLED"===c.state.status?Rm(c,c,d,f,g):"REJECTED"===c.state.status&&Sm(c,c,e,f,g)}))};
Qm.prototype.catch=function(a){return this.then(void 0,a)};
function Rm(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Qm?Tm(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Sm(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Qm?Tm(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Tm(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Qm?Tm(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Um(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Vm(a){return new Promise(function(b,c){Um(a,b,c)})}
function Wm(a){return new Qm(new Pm(function(b,c){Um(a,b,c)}))}
;function Xm(a,b){return new Qm(new Pm(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;function Ym(a,b){this.i=a;this.options=b;this.transactionCount=0;this.l=Math.round(P());this.j=!1}
l=Ym.prototype;l.add=function(a,b,c){return Zm(this,[a],{mode:"readwrite",U:!0},function(d){return d.objectStore(a).add(b,c)})};
l.clear=function(a){return Zm(this,[a],{mode:"readwrite",U:!0},function(b){return b.objectStore(a).clear()})};
l.close=function(){this.i.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
l.count=function(a,b){return Zm(this,[a],{mode:"readonly",U:!0},function(c){return c.objectStore(a).count(b)})};
function $m(a,b,c){a=a.i.createObjectStore(b,c);return new an(a)}
l.delete=function(a,b){return Zm(this,[a],{mode:"readwrite",U:!0},function(c){return c.objectStore(a).delete(b)})};
l.get=function(a,b){return Zm(this,[a],{mode:"readonly",U:!0},function(c){return c.objectStore(a).get(b)})};
function bn(a,b){return Zm(a,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(c){c=c.objectStore("LogsRequestsStore");return Wm(c.i.put(b,void 0))})}
l.objectStoreNames=function(){return Array.from(this.i.objectStoreNames)};
function Zm(a,b,c,d){var e,f,g,h,k,m,q,r,w,u,A,E;return x(function(F){switch(F.i){case 1:var N={mode:"readonly",U:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?N.mode=c:Object.assign(N,c);e=N;a.transactionCount++;f=e.U?3:1;g=0;case 2:if(h){F.u(3);break}g++;k=Math.round(P());ya(F,4);m=a.i.transaction(b,e.mode);N=new cn(m);N=dn(N,d);return v(F,N,6);case 6:return q=F.j,r=Math.round(P()),en(a,k,r,g,void 0,b.join(),e),F.return(q);case 4:w=Aa(F);u=Math.round(P());A=Lm(w,a.i.name,b.join(),a.i.version);
if((E=A instanceof Hm&&!A.i)||g>=f)en(a,k,u,g,A,b.join(),e),h=A;F.u(2);break;case 3:return F.return(Promise.reject(h))}})}
function en(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Hm&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&wm("QUOTA_EXCEEDED",{dbName:Am(a.i.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Hm&&"UNKNOWN_ABORT"===e.type&&(c-=a.l,0>c&&c>=Math.pow(2,31)&&(c=0),wm("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.j=!0),fn(a,!1,d,f,b,g.tag),vm(e)):fn(a,!0,d,f,b,g.tag)}
function fn(a,b,c,d,e,f){wm("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.j,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
l.getName=function(){return this.i.name};
function an(a){this.i=a}
l=an.prototype;l.add=function(a,b){return Wm(this.i.add(a,b))};
l.autoIncrement=function(){return this.i.autoIncrement};
l.clear=function(){return Wm(this.i.clear()).then(function(){})};
l.count=function(a){return Wm(this.i.count(a))};
function gn(a,b){return hn(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
l.delete=function(a){return a instanceof IDBKeyRange?gn(this,a):Wm(this.i.delete(a))};
l.get=function(a){return Wm(this.i.get(a))};
l.index=function(a){try{return new jn(this.i.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new Jm(a,this.i.name);throw b;}};
l.getName=function(){return this.i.name};
l.keyPath=function(){return this.i.keyPath};
function hn(a,b,c){a=a.i.openCursor(b.query,b.direction);return kn(a).then(function(d){return Xm(d,c)})}
function cn(a){var b=this;this.i=a;this.l=new Map;this.j=!1;this.done=new Promise(function(c,d){b.i.addEventListener("complete",function(){c()});
b.i.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.i.error)});
b.i.addEventListener("abort",function(){var e=b.i.error;if(e)d(e);else if(!b.j){e=Hm;for(var f=b.i.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.i.db.name,mode:b.i.mode});d(e)}})})}
function dn(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return p(d).next().value})}
cn.prototype.abort=function(){this.i.abort();this.j=!0;throw new Hm("EXPLICIT_ABORT");};
cn.prototype.objectStore=function(a){a=this.i.objectStore(a);var b=this.l.get(a);b||(b=new an(a),this.l.set(a,b));return b};
function jn(a){this.i=a}
l=jn.prototype;l.count=function(a){return Wm(this.i.count(a))};
l.delete=function(a){return ln(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
l.get=function(a){return Wm(this.i.get(a))};
l.getKey=function(a){return Wm(this.i.getKey(a))};
l.keyPath=function(){return this.i.keyPath};
l.unique=function(){return this.i.unique};
function ln(a,b,c){a=a.i.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return kn(a).then(function(d){return Xm(d,c)})}
function mn(a,b){this.request=a;this.cursor=b}
function kn(a){return Wm(a).then(function(b){return b?new mn(a,b):null})}
l=mn.prototype;l.advance=function(a){this.cursor.advance(a);return kn(this.request)};
l.continue=function(a){this.cursor.continue(a);return kn(this.request)};
l.delete=function(){return Wm(this.cursor.delete()).then(function(){})};
l.getKey=function(){return this.cursor.key};
l.getValue=function(){return this.cursor.value};
l.update=function(a){return Wm(this.cursor.update(a))};function nn(a,b,c){return new Promise(function(d,e){function f(){w||(w=new Ym(g.result,{closed:r}));return w}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.blocked,k=c.blocking,m=c.nd,q=c.upgrade,r=c.closed,w;g.addEventListener("upgradeneeded",function(u){try{if(null===u.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");u.dataLoss&&"none"!==u.dataLoss&&wm("IDB_DATA_CORRUPTED",{reason:u.dataLossMessage||"unknown reason",dbName:Am(a)});var A=f(),E=new cn(g.transaction);
q&&q(A,function(F){return u.oldVersion<F&&u.newVersion>=F},E);
E.done.catch(function(F){e(F)})}catch(F){e(F)}});
g.addEventListener("success",function(){var u=g.result;k&&u.addEventListener("versionchange",function(){k(f())});
u.addEventListener("close",function(){wm("IDB_UNEXPECTEDLY_CLOSED",{dbName:Am(a),dbVersion:u.version});m&&m()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function on(a,b,c){c=void 0===c?{}:c;return nn(a,b,c)}
function pn(a,b){b=void 0===b?{}:b;var c,d,e,f;return x(function(g){if(1==g.i)return ya(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.blocked)&&c.addEventListener("blocked",function(){e()}),v(g,Vm(c),4);
if(2!=g.i)return za(g,0);f=Aa(g);throw Lm(f,a,"",-1);})}
;function qn(a){return new Promise(function(b){gm(function(){b()},a)})}
function rn(a,b){this.name=a;this.options=b;this.m=!0;this.s=this.o=0;this.j=500}
rn.prototype.l=function(a,b,c){c=void 0===c?{}:c;return on(a,b,c)};
rn.prototype.delete=function(a){a=void 0===a?{}:a;return pn(this.name,a)};
function sn(a,b){return new Hm("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function tn(a,b){if(!b)throw Mm("openWithToken",Am(a.name));return un(a)}
function un(a){function b(){var f,g,h,k,m,q,r,w,u,A;return x(function(E){switch(E.i){case 1:return g=null!=(f=Error().stack)?f:"",ya(E,2),v(E,a.l(a.name,a.options.version,d),4);case 4:h=E.j;for(var F=a.options,N=[],O=p(Object.keys(F.Ia)),R=O.next();!R.done;R=O.next()){R=R.value;var U=F.Ia[R],ca=void 0===U.Vc?Number.MAX_VALUE:U.Vc;!(h.i.version>=U.jb)||h.i.version>=ca||h.i.objectStoreNames.contains(R)||N.push(R)}k=N;if(0===k.length){E.u(5);break}m=Object.keys(a.options.Ia);q=h.objectStoreNames();if(a.s<
Ik("ytidb_reopen_db_retries",0))return a.s++,h.close(),vm(new Hm("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:q})),E.return(b());if(!(a.o<Ik("ytidb_remake_db_retries",1))){E.u(6);break}a.o++;if(!M("ytidb_remake_db_enable_backoff_delay")){E.u(7);break}return v(E,qn(a.j),8);case 8:a.j*=2;case 7:return v(E,a.delete(),9);case 9:return vm(new Hm("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:q})),E.return(b());
case 6:throw new Im(q,m);case 5:return E.return(h);case 2:r=Aa(E);if(r instanceof DOMException?"VersionError"!==r.name:"DOMError"in self&&r instanceof DOMError?"VersionError"!==r.name:!(r instanceof Object&&"message"in r)||"An attempt was made to open a database using a lower version than the existing version."!==r.message){E.u(10);break}return v(E,a.l(a.name,void 0,Object.assign({},d,{upgrade:void 0})),11);case 11:w=E.j;u=w.i.version;if(void 0!==a.options.version&&u>a.options.version+1)throw w.close(),
a.m=!1,sn(a,u);return E.return(w);case 10:throw c(),r instanceof Error&&!M("ytidb_async_stack_killswitch")&&(r.stack=r.stack+"\n"+g.substring(g.indexOf("\n")+1)),Lm(r,a.name,"",null!=(A=a.options.version)?A:-1);}})}
function c(){a.i===e&&(a.i=void 0)}
if(!a.m)throw sn(a);if(a.i)return a.i;var d={blocking:function(f){f.close()},
closed:c,nd:c,upgrade:a.options.upgrade};var e=b();a.i=e;return a.i}
;var vn=new rn("YtIdbMeta",{Ia:{databases:{jb:1}},upgrade:function(a,b){b(1)&&$m(a,"databases",{keyPath:"actualName"})}});
function wn(a,b){var c;return x(function(d){if(1==d.i)return v(d,tn(vn,b),2);c=d.j;return d.return(Zm(c,["databases"],{U:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Wm(f.i.put(a,void 0)).then(function(){})})}))})}
function xn(a,b){var c;return x(function(d){if(1==d.i)return a?v(d,tn(vn,b),2):d.return();c=d.j;return d.return(c.delete("databases",a))})}
function yn(a,b){var c,d;return x(function(e){return 1==e.i?(c=[],v(e,tn(vn,b),2)):3!=e.i?(d=e.j,v(e,Zm(d,["databases"],{U:!0,mode:"readonly"},function(f){c.length=0;return hn(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function zn(a){return yn(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function An(a,b,c){return yn(function(d){return c?void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)},b)}
function Bn(a){var b,c;return x(function(d){if(1==d.i)return b=ym("YtIdbMeta hasAnyMeta other"),v(d,yn(function(e){return void 0!==e.userIdentifier&&e.userIdentifier!==b},a),2);
c=d.j;return d.return(0<c.length)})}
;var Cn,Dn=new function(){}(new function(){});
function En(){var a,b,c,d;return x(function(e){switch(e.i){case 1:a=nm();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=km)f=/WebKit\/([0-9]+)/.exec(Tb()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Tb()),f=!(f&&602<=parseInt(f[1],10)));if(f||Nc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
ya(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return v(e,wn(d,Dn),4);case 4:return v(e,xn("yt-idb-test-do-not-use",Dn),5);case 5:return e.return(!0);case 2:return Aa(e),e.return(!1)}})}
function Fn(){if(void 0!==Cn)return Cn;qm=!0;return Cn=En().then(function(a){qm=!1;var b;if(null!=(b=mm())&&b.i){var c;b={hasSucceededOnce:(null==(c=nm())?void 0:c.hasSucceededOnce)||a};var d;null==(d=mm())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function Gn(){return B("ytglobal.idbToken_")||void 0}
function Hn(){var a=Gn();return a?Promise.resolve(a):Fn().then(function(b){(b=b?Dn:void 0)&&z("ytglobal.idbToken_",b);return b})}
;var In=0;function Jn(a,b){In||(In=Xh.S(function(){var c,d,e,f,g;return x(function(h){switch(h.i){case 1:return v(h,Hn(),2);case 2:c=h.j;if(!c)return h.return();d=!0;ya(h,3);return v(h,An(a,c,b),5);case 5:e=h.j;if(!e.length){d=!1;h.u(6);break}f=e[0];return v(h,pn(f.actualName),7);case 7:return v(h,xn(f.actualName,c),6);case 6:za(h,4);break;case 3:g=Aa(h),vm(g),d=!1;case 4:Xh.fa(In),In=0,d&&Jn(a,b),h.i=0}})}))}
function Kn(){var a;return x(function(b){return 1==b.i?v(b,Hn(),2):(a=b.j)?b.return(Bn(a)):b.return(!1)})}
new Bh;function Ln(a){if(!xm())throw a=new Hm("AUTH_INVALID",{dbName:a}),vm(a),a;var b=ym();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Mn(a,b,c,d){var e,f,g,h,k,m;return x(function(q){switch(q.i){case 1:return f=null!=(e=Error().stack)?e:"",v(q,Hn(),2);case 2:g=q.j;if(!g)throw h=Mm("openDbImpl",a,b),M("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),vm(h),h;zm(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Ln(a);ya(q,3);return v(q,wn(k,g),5);case 5:return v(q,on(k.actualName,b,d),6);case 6:return q.return(q.j);case 3:return m=Aa(q),ya(q,7),v(q,xn(k.actualName,g),9);case 9:za(q,
8);break;case 7:Aa(q);case 8:throw m;}})}
function Nn(a,b,c){c=void 0===c?{}:c;return Mn(a,b,!1,c)}
function On(a,b,c){c=void 0===c?{}:c;return Mn(a,b,!0,c)}
function Pn(a,b){b=void 0===b?{}:b;var c,d;return x(function(e){if(1==e.i)return v(e,Hn(),2);if(3!=e.i){c=e.j;if(!c)return e.return();zm(a);d=Ln(a);return v(e,pn(d.actualName,b),3)}return v(e,xn(d.actualName,c),0)})}
function Qn(a,b,c){a=a.map(function(d){return x(function(e){return 1==e.i?v(e,pn(d.actualName,b),2):v(e,xn(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Rn(){var a=void 0===a?{}:a;var b,c;return x(function(d){if(1==d.i)return v(d,Hn(),2);if(3!=d.i){b=d.j;if(!b)return d.return();zm("LogsDatabaseV2");return v(d,zn(b),3)}c=d.j;return v(d,Qn(c,a,b),0)})}
function Sn(a,b){b=void 0===b?{}:b;var c;return x(function(d){if(1==d.i)return v(d,Hn(),2);if(3!=d.i){c=d.j;if(!c)return d.return();zm(a);return v(d,pn(a,b),3)}return v(d,xn(a,c),0)})}
;function Tn(a){this.Sa=this.i=!1;this.potentialEsfErrorCounter=this.j=0;this.handleError=function(){};
this.Aa=function(){};
this.now=Date.now;this.Ga=!1;var b;this.kc=null!=(b=a.kc)?b:100;var c;this.fc=null!=(c=a.fc)?c:1;var d;this.dc=null!=(d=a.dc)?d:2592E6;var e;this.ac=null!=(e=a.ac)?e:12E4;var f;this.ec=null!=(f=a.ec)?f:5E3;var g;this.H=null!=(g=a.H)?g:void 0;this.Xa=!!a.Xa;var h;this.Va=null!=(h=a.Va)?h:.1;var k;this.cb=null!=(k=a.cb)?k:10;a.handleError&&(this.handleError=a.handleError);a.Aa&&(this.Aa=a.Aa);a.Ga&&(this.Ga=a.Ga);a.Sa&&(this.Sa=a.Sa);this.I=a.I;this.Z=a.Z;this.O=a.O;this.M=a.M;this.ia=a.ia;this.wb=
a.wb;this.vb=a.vb;Un(this)&&(!this.I||this.I("networkless_logging"))&&Vn(this)}
function Vn(a){Un(a)&&!a.Ga&&(a.i=!0,a.Xa&&Math.random()<=a.Va&&a.O.zc(a.H),Wn(a),a.M.L()&&a.Ma(),a.M.aa(a.wb,a.Ma.bind(a)),a.M.aa(a.vb,a.Ib.bind(a)))}
l=Tn.prototype;l.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(Un(this)&&this.i){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.O.set(d,this.H).then(function(e){d.id=e;c.M.L()&&Xn(c,d)}).catch(function(e){Xn(c,d);
Yn(c,e)})}else this.ia(a,b)};
l.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(Un(this)&&this.i){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.I&&this.I("nwl_skip_retry")&&(e.skipRetry=c);if(this.M.L()||this.I&&this.I("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return x(function(k){if(1==k.i)return v(k,d.O.set(e,d.H).catch(function(m){Yn(d,m)}),2);
f(g,h);k.i=0})}}this.ia(a,b,e.skipRetry)}else this.O.set(e,this.H).catch(function(g){d.ia(a,b,e.skipRetry);
Yn(d,g)})}else this.ia(a,b,this.I&&this.I("nwl_skip_retry")&&c)};
l.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(Un(this)&&this.i){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.O.za(d.id,c.H):e=!0;c.M.ha&&c.I&&c.I("vss_network_hint")&&c.M.ha(!0);f(g,h)};
this.ia(d.url,d.options);this.O.set(d,this.H).then(function(g){d.id=g;e&&c.O.za(d.id,c.H)}).catch(function(g){Yn(c,g)})}else this.ia(a,b)};
l.Ma=function(){var a=this;if(!Un(this))throw Mm("throttleSend");this.j||(this.j=this.Z.S(function(){var b;return x(function(c){if(1==c.i)return v(c,a.O.Sb("NEW",a.H),2);if(3!=c.i)return b=c.j,b?v(c,Xn(a,b),3):(a.Ib(),c.return());a.j&&(a.j=0,a.Ma());c.i=0})},this.kc))};
l.Ib=function(){this.Z.fa(this.j);this.j=0};
function Xn(a,b){var c,d;return x(function(e){switch(e.i){case 1:if(!Un(a))throw c=Mm("immediateSend"),c;if(void 0===b.id){e.u(2);break}return v(e,a.O.Pc(b.id,a.H),3);case 3:(d=e.j)?b=d:a.Aa(Error("The request cannot be found in the database."));case 2:if(Zn(a,b,a.dc)){e.u(4);break}a.Aa(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.u(5);break}return v(e,a.O.za(b.id,a.H),5);case 5:return e.return();case 4:b.skipRetry||(b=$n(a,b));if(!b){e.u(0);break}if(!b.skipRetry||
void 0===b.id){e.u(8);break}return v(e,a.O.za(b.id,a.H),8);case 8:a.ia(b.url,b.options,!!b.skipRetry),e.i=0}})}
function $n(a,b){if(!Un(a))throw Mm("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k;return x(function(m){switch(m.i){case 1:g=ao(f);if(!(a.I&&a.I("nwl_consider_error_code")&&g||a.I&&!a.I("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.cb)){m.u(2);break}if(!a.M.Ka){m.u(3);break}return v(m,a.M.Ka(),3);case 3:if(a.M.L()){m.u(2);break}c(e,f);if(!a.I||!a.I("nwl_consider_error_code")||void 0===(null==(h=b)?void 0:h.id)){m.u(6);break}return v(m,a.O.zb(b.id,a.H,!1),6);case 6:return m.return();case 2:if(a.I&&a.I("nwl_consider_error_code")&&
!g&&a.potentialEsfErrorCounter>a.cb)return m.return();a.potentialEsfErrorCounter++;if(void 0===(null==(k=b)?void 0:k.id)){m.u(8);break}return b.sendCount<a.fc?v(m,a.O.zb(b.id,a.H),12):v(m,a.O.za(b.id,a.H),8);case 12:a.Z.S(function(){a.M.L()&&a.Ma()},a.ec);
case 8:c(e,f),m.i=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return x(function(h){if(1==h.i)return void 0===(null==(g=b)?void 0:g.id)?h.u(2):v(h,a.O.za(b.id,a.H),2);a.M.ha&&a.I&&a.I("vss_network_hint")&&a.M.ha(!0);d(e,f);h.i=0})};
return b}
function Zn(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function Wn(a){if(!Un(a))throw Mm("retryQueuedRequests");a.O.Sb("QUEUED",a.H).then(function(b){b&&!Zn(a,b,a.ac)?a.Z.S(function(){return x(function(c){if(1==c.i)return void 0===b.id?c.u(2):v(c,a.O.zb(b.id,a.H),2);Wn(a);c.i=0})}):a.M.L()&&a.Ma()})}
function Yn(a,b){a.oc&&!a.M.L()?a.oc(b):a.handleError(b)}
function Un(a){return!!a.H||a.Sa}
function ao(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
;function bo(a,b){this.version=a;this.args=b}
;function co(a,b){this.topic=a;this.i=b}
co.prototype.toString=function(){return this.topic};var eo=B("ytPubsub2Pubsub2Instance")||new K;K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.Da;K.prototype.publish=K.prototype.qa;K.prototype.clear=K.prototype.clear;z("ytPubsub2Pubsub2Instance",eo);var fo=B("ytPubsub2Pubsub2SubscribedKeys")||{};z("ytPubsub2Pubsub2SubscribedKeys",fo);var go=B("ytPubsub2Pubsub2TopicToKeys")||{};z("ytPubsub2Pubsub2TopicToKeys",go);var ho=B("ytPubsub2Pubsub2IsAsync")||{};z("ytPubsub2Pubsub2IsAsync",ho);
z("ytPubsub2Pubsub2SkipSubKey",null);function io(a,b){var c=jo();c&&c.publish.call(c,a.toString(),a,b)}
function ko(a){var b=lo,c=jo();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=B("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(fo[d])try{if(f&&b instanceof co&&b!=e)try{var h=b.i,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.oa){var m=new h;h.oa=m.version}var q=h.oa}catch(F){}if(!q||k.version!=q)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{q=Reflect;var r=q.construct;
var w=k.args,u=w.length;if(0<u){var A=Array(u);for(k=0;k<u;k++)A[k]=w[k];var E=A}else E=[];f=r.call(q,h,E)}catch(F){throw F.message="yt.pubsub2.Data.deserialize(): "+F.message,F;}}catch(F){throw F.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+F.message,F;}a.call(window,f)}catch(F){Ok(F)}},ho[b.toString()]?B("yt.scheduler.instance")?Xh.S(g):hl(g,0):g())});
fo[d]=!0;go[b.toString()]||(go[b.toString()]=[]);go[b.toString()].push(d);return d}
function mo(){var a=no,b=ko(function(c){a.apply(void 0,arguments);oo(b)});
return b}
function oo(a){var b=jo();b&&("number"===typeof a&&(a=[a]),fb(a,function(c){b.unsubscribeByKey(c);delete fo[c]}))}
function jo(){return B("ytPubsub2Pubsub2Instance")}
;function po(a,b){rn.call(this,a,b);this.options=b;zm(a)}
t(po,rn);function qo(a,b){var c;return function(){c||(c=new po(a,b));return c}}
po.prototype.l=function(a,b,c){c=void 0===c?{}:c;return(this.options.Ab?On:Nn)(a,b,Object.assign({},c))};
po.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.Ab?Sn:Pn)(this.name,a)};
function ro(a,b){return qo(a,b)}
;var so;
function to(){if(so)return so();var a={};so=ro("LogsDatabaseV2",{Ia:(a.LogsRequestsStore={jb:2},a),Ab:!1,upgrade:function(b,c,d){c(2)&&$m(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.i.indexNames.contains("newRequest")&&d.i.deleteIndex("newRequest"),d.i.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.i.objectStoreNames.contains("sapisid")&&b.i.deleteObjectStore("sapisid");c(9)&&b.i.objectStoreNames.contains("SWHealthLog")&&b.i.deleteObjectStore("SWHealthLog")},
version:9});return so()}
;function uo(a){return tn(to(),a)}
function vo(a,b){var c,d,e,f;return x(function(g){if(1==g.i)return c={startTime:P(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},v(g,uo(b),2);if(3!=g.i)return d=g.j,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:L("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),v(g,bn(d,e),3);f=g.j;c.pd=P();wo(c);return g.return(f)})}
function xo(a,b){var c,d,e,f,g,h,k;return x(function(m){if(1==m.i)return c={startTime:P(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},v(m,uo(b),2);if(3!=m.i)return d=m.j,e=L("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,P()],h=IDBKeyRange.bound(f,g),k=void 0,v(m,Zm(d,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(q){return ln(q.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(r){r.getValue()&&(k=r.getValue(),"NEW"===a&&(k.status="QUEUED",
r.update(k)))})}),3);
c.pd=P();wo(c);return m.return(k)})}
function yo(a,b){var c;return x(function(d){if(1==d.i)return v(d,uo(b),2);c=d.j;return d.return(Zm(c,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Wm(f.i.put(g,void 0)).then(function(){return g})})}))})}
function zo(a,b,c){c=void 0===c?!0:c;var d;return x(function(e){if(1==e.i)return v(e,uo(b),2);d=e.j;return e.return(Zm(d,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){return h?(h.status="NEW",c&&(h.sendCount+=1),Wm(g.i.put(h,void 0)).then(function(){return h})):Qm.resolve(void 0)})}))})}
function Ao(a,b){var c;return x(function(d){if(1==d.i)return v(d,uo(b),2);c=d.j;return d.return(c.delete("LogsRequestsStore",a))})}
function Bo(a){var b,c;return x(function(d){if(1==d.i)return v(d,uo(a),2);b=d.j;c=P()-2592E6;return v(d,Zm(b,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(e){return hn(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Co(){return x(function(a){return v(a,Rn(),0)})}
function wo(a){M("nwl_csi_killswitch")||.01>=Math.random()&&io("nwl_transaction_latency_payload",a)}
;var Do={},Eo=ro("ServiceWorkerLogsDatabase",{Ia:(Do.SWHealthLog={jb:1},Do),Ab:!0,upgrade:function(a,b){b(1)&&$m(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}).i.createIndex("swHealthNewRequest",["interface","timestamp"],{unique:!1})},
version:1});function Fo(a){return tn(Eo(),a)}
function Go(a){var b,c;return x(function(d){if(1==d.i)return v(d,Fo(a),2);b=d.j;c=P()-2592E6;return v(d,Zm(b,["SWHealthLog"],{mode:"readwrite",U:!0},function(e){return hn(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Ho(a){var b;return x(function(c){if(1==c.i)return v(c,Fo(a),2);b=c.j;return v(c,b.clear("SWHealthLog"),0)})}
;var Io={},Jo=0;
function Ko(a){var b=void 0===b?"":b;var c=void 0===c?!1:c;if(a)if(b)rl(a,void 0,"POST",b);else if(L("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))rl(a,void 0,"GET","",void 0,void 0,c);else{b:{try{var d=new bb({url:a});if(d.l&&d.j||d.m){var e=mc(nc(5,a)),f;if(!(f=!e||!e.endsWith("/aclk"))){var g=a.search(yc),h=xc(a,0,"ri",g);if(0>h)var k=null;else{var m=a.indexOf("&",h);if(0>m||m>g)m=g;k=decodeURIComponent(a.slice(h+3,-1!==m?m:0).replace(/\+/g," "))}f="1"!==k}var q=!f;break b}}catch(w){}q=!1}if(q){b:{try{if(window.navigator&&
window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var r=!0;break b}}catch(w){}r=!1}b=r?!0:!1}else b=!1;b||Lo(a)}}
function Lo(a){var b=new Image,c=""+Jo++;Io[c]=b;b.onload=b.onerror=function(){delete Io[c]};
b.src=a}
;function Mo(){this.i=new Map;this.j=!1}
function No(){if(!Mo.i){var a=B("yt.networkRequestMonitor.instance")||new Mo;z("yt.networkRequestMonitor.instance",a);Mo.i=a}return Mo.i}
Mo.prototype.requestComplete=function(a,b){b&&(this.j=!0);a=this.removeParams(a);this.i.get(a)||this.i.set(a,b)};
Mo.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.i.get(a))?!1:!1===a&&this.j?!0:null};
Mo.prototype.removeParams=function(a){return a.split("?")[0]};
Mo.prototype.removeParams=Mo.prototype.removeParams;Mo.prototype.isEndpointCFR=Mo.prototype.isEndpointCFR;Mo.prototype.requestComplete=Mo.prototype.requestComplete;Mo.getInstance=No;var Oo;function Po(){Oo||(Oo=new Xl("yt.offline"));return Oo}
function Qo(a){if(M("offline_error_handling")){var b=Po().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Po().set("errors",b,2592E3,!0)}}
;function Ro(){af.call(this);var a=this;this.l=!1;this.j=Wh();this.j.aa("networkstatus-online",function(){if(a.l&&M("offline_error_handling")){var b=Po().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new Q(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;Ok(d)}Po().set("errors",{},2592E3,!0)}}})}
t(Ro,af);function So(){if(!Ro.i){var a=B("yt.networkStatusManager.instance")||new Ro;z("yt.networkStatusManager.instance",a);Ro.i=a}return Ro.i}
l=Ro.prototype;l.L=function(){return this.j.L()};
l.ha=function(a){this.j.j=a};
l.Jc=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
l.Dc=function(){this.l=!0};
l.aa=function(a,b){return this.j.aa(a,b)};
l.Ka=function(a){a=Uh(this.j,a);a.then(function(b){M("use_cfr_monitor")&&No().requestComplete("generate_204",b)});
return a};
Ro.prototype.sendNetworkCheckRequest=Ro.prototype.Ka;Ro.prototype.listen=Ro.prototype.aa;Ro.prototype.enableErrorFlushing=Ro.prototype.Dc;Ro.prototype.getWindowStatus=Ro.prototype.Jc;Ro.prototype.networkStatusHint=Ro.prototype.ha;Ro.prototype.isNetworkAvailable=Ro.prototype.L;Ro.getInstance=So;function To(a){a=void 0===a?{}:a;af.call(this);var b=this;this.j=this.s=0;this.l=So();var c=B("yt.networkStatusManager.instance.listen").bind(this.l);c&&(a.fb?(this.fb=a.fb,c("networkstatus-online",function(){Uo(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Uo(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){bf(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){bf(b,"publicytnetworkstatus-offline")})))}
t(To,af);To.prototype.L=function(){var a=B("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.l)():!0};
To.prototype.ha=function(a){var b=B("yt.networkStatusManager.instance.networkStatusHint").bind(this.l);b&&b(a)};
To.prototype.Ka=function(a){var b=this,c;return x(function(d){c=B("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.l);return M("skip_network_check_if_cfr")&&No().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.ha((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.L())})):c?d.return(c(a)):d.return(!0)})};
function Uo(a,b){a.fb?a.j?(Xh.fa(a.s),a.s=Xh.S(function(){a.o!==b&&(bf(a,b),a.o=b,a.j=P())},a.fb-(P()-a.j))):(bf(a,b),a.o=b,a.j=P()):bf(a,b)}
;var Vo;function Wo(){Tn.call(this,{O:{zc:Bo,za:Ao,Sb:xo,Pc:yo,zb:zo,set:vo},M:Xo(),handleError:Ok,Aa:Pk,ia:Yo,now:P,oc:Qo,Z:jm(),wb:"publicytnetworkstatus-online",vb:"publicytnetworkstatus-offline",Xa:!0,Va:.1,cb:Ik("potential_esf_error_limit",10),I:M,Ga:!(xm()&&Zo())});this.l=new Bh;M("networkless_immediately_drop_all_requests")&&Co();Sn("LogsDatabaseV2")}
t(Wo,Tn);function $o(){var a=B("yt.networklessRequestController.instance");a||(a=new Wo,z("yt.networklessRequestController.instance",a),M("networkless_logging")&&Hn().then(function(b){a.H=b;Vn(a);a.l.resolve();a.Xa&&Math.random()<=a.Va&&a.H&&Go(a.H);M("networkless_immediately_drop_sw_health_store")&&ap(a)}));
return a}
Wo.prototype.writeThenSend=function(a,b){b||(b={});xm()||(this.i=!1);Tn.prototype.writeThenSend.call(this,a,b)};
Wo.prototype.sendThenWrite=function(a,b,c){b||(b={});xm()||(this.i=!1);Tn.prototype.sendThenWrite.call(this,a,b,c)};
Wo.prototype.sendAndWrite=function(a,b){b||(b={});xm()||(this.i=!1);Tn.prototype.sendAndWrite.call(this,a,b)};
Wo.prototype.awaitInitialization=function(){return this.l.promise};
function ap(a){var b;x(function(c){if(!a.H)throw b=Mm("clearSWHealthLogsDb"),b;return c.return(Ho(a.H).catch(function(d){a.handleError(d)}))})}
function Yo(a,b,c){M("use_cfr_monitor")&&bp(a,b);if(M("use_request_time_ms_header"))b.headers&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(P())));else{var d;if(null==(d=b.postParams)?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(P())}c&&0===Object.keys(b).length?Ko(a):ol(a,b)}
function Xo(){Vo||(Vo=new To({Oc:!0,Ec:!0}));return Vo}
function bp(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){No().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){No().requestComplete(a,!0);d(e,f)}}
function Zo(){return"www.youtube-nocookie.com"!==oc(document.location.toString())}
;var cp=!1,dp=0,ep=0,fp,gp=y.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:cp,potentialEsfErrorCounter:ep};z("ytNetworklessLoggingInitializationOptions",gp);
function hp(){var a;x(function(b){switch(b.i){case 1:return v(b,Hn(),2);case 2:a=b.j;if(!a||!xm()&&!M("nwl_init_require_datasync_id_killswitch")||!Zo()){b.u(0);break}cp=!0;gp.isNwlInitialized=cp;if(!M("use_new_nwl_initialization")){b.u(4);break}return v(b,$o().awaitInitialization(),5);case 5:return b.return();case 4:return v(b,Sn("LogsDatabaseV2"),6);case 6:if(!(.1>=Math.random())){b.u(7);break}return v(b,Bo(a),8);case 8:return v(b,Go(a),7);case 7:ip();jp().L()&&kp();jp().aa("publicytnetworkstatus-online",
kp);jp().aa("publicytnetworkstatus-offline",lp);if(!M("networkless_immediately_drop_sw_health_store")){b.u(10);break}return v(b,mp(),10);case 10:if(M("networkless_immediately_drop_all_requests"))return v(b,Co(),0);b.u(0)}})}
function np(a,b){function c(d){var e=jp().L();if(!op()||!d||e&&M("vss_networkless_bypass_write"))pp(a,b);else{var f={url:a,options:b,timestamp:P(),status:"NEW",sendCount:0};vo(f,d).then(function(g){f.id=g;jp().L()&&qp(f)}).catch(function(g){qp(f);
jp().L()?Ok(g):Qo(g)})}}
b=void 0===b?{}:b;M("skip_is_supported_killswitch")?Hn().then(function(d){c(d)}):c(Gn())}
function rp(a,b){function c(d){if(op()&&d){var e={url:a,options:b,timestamp:P(),status:"NEW",sendCount:0},f=!1,g=b.onSuccess?b.onSuccess:function(){};
e.options.onSuccess=function(k,m){M("use_cfr_monitor")&&No().requestComplete(e.url,!0);void 0!==e.id?Ao(e.id,d):f=!0;M("vss_network_hint")&&jp().ha(!0);g(k,m)};
if(M("use_cfr_monitor")){var h=b.onError?b.onError:function(){};
e.options.onError=function(k,m){No().requestComplete(e.url,!1);h(k,m)}}pp(e.url,e.options);
vo(e,d).then(function(k){e.id=k;f&&Ao(e.id,d)}).catch(function(k){jp().L()?Ok(k):Qo(k)})}else pp(a,b)}
b=void 0===b?{}:b;M("skip_is_supported_killswitch")?Hn().then(function(d){c(d)}):c(Gn())}
function kp(){var a=Gn();if(!a)throw Mm("throttleSend");dp||(dp=Xh.S(function(){var b;return x(function(c){if(1==c.i)return v(c,xo("NEW",a),2);if(3!=c.i)return b=c.j,b?v(c,qp(b),3):(lp(),c.return());dp&&(dp=0,kp());c.i=0})},100))}
function lp(){Xh.fa(dp);dp=0}
function qp(a){var b,c,d;return x(function(e){switch(e.i){case 1:b=Gn();if(!b)throw c=Mm("immediateSend"),c;if(void 0===a.id){e.u(2);break}return v(e,yo(a.id,b),3);case 3:(d=e.j)?a=d:Pk(Error("The request cannot be found in the database."));case 2:if(sp(a,2592E6)){e.u(4);break}Pk(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===a.id){e.u(5);break}return v(e,Ao(a.id,b),5);case 5:return e.return();case 4:a.skipRetry||(a=tp(a));var f=a;if(M("use_request_time_ms_header")){var g;
if(null==f?0:null==(g=f.options)?0:g.headers)f.options.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(P()))}else{var h,k;if(null==f?0:null==(h=f.options)?0:null==(k=h.postParams)?0:k.requestTimeMs)f.options.postParams.requestTimeMs=Math.round(P())}a=f;if(!a){e.u(0);break}if(!a.skipRetry||void 0===a.id){e.u(8);break}return v(e,Ao(a.id,b),8);case 8:pp(a.url,a.options,!!a.skipRetry),e.i=0}})}
function tp(a){var b=Gn();if(!b)throw Mm("updateRequestHandlers");var c=a.options.onError?a.options.onError:function(){};
a.options.onError=function(e,f){var g,h,k;return x(function(m){switch(m.i){case 1:M("use_cfr_monitor")&&No().requestComplete(a.url,!1);g=ao(f);if(!(M("nwl_consider_error_code")&&g||!M("nwl_consider_error_code")&&up()<=Ik("potential_esf_error_limit",10))){m.u(2);break}if(M("skip_checking_network_on_cfr_failure")&&(!M("skip_checking_network_on_cfr_failure")||No().isEndpointCFR(a.url))){m.u(3);break}return v(m,jp().Ka(),3);case 3:if(jp().L()){m.u(2);break}c(e,f);if(!M("nwl_consider_error_code")||void 0===
(null==(h=a)?void 0:h.id)){m.u(6);break}return v(m,zo(a.id,b,!1),6);case 6:return m.return();case 2:if(M("nwl_consider_error_code")&&!g&&up()>Ik("potential_esf_error_limit",10))return m.return();B("ytNetworklessLoggingInitializationOptions")&&gp.potentialEsfErrorCounter++;ep++;if(void 0===(null==(k=a)?void 0:k.id)){m.u(8);break}return 1>a.sendCount?v(m,zo(a.id,b),12):v(m,Ao(a.id,b),8);case 12:Xh.S(function(){jp().L()&&kp()},5E3);
case 8:c(e,f),m.i=0}})};
var d=a.options.onSuccess?a.options.onSuccess:function(){};
a.options.onSuccess=function(e,f){var g;return x(function(h){if(1==h.i)return M("use_cfr_monitor")&&No().requestComplete(a.url,!0),void 0===(null==(g=a)?void 0:g.id)?h.u(2):v(h,Ao(a.id,b),2);M("vss_network_hint")&&jp().ha(!0);d(e,f);h.i=0})};
return a}
function sp(a,b){a=a.timestamp;return P()-a>=b?!1:!0}
function ip(){var a=Gn();if(!a)throw Mm("retryQueuedRequests");xo("QUEUED",a).then(function(b){b&&!sp(b,12E4)?Xh.S(function(){return x(function(c){if(1==c.i)return void 0===b.id?c.u(2):v(c,zo(b.id,a),2);ip();c.i=0})}):jp().L()&&kp()})}
function mp(){var a,b;return x(function(c){a=Gn();if(!a)throw b=Mm("clearSWHealthLogsDb"),b;return c.return(Ho(a).catch(function(d){Ok(d)}))})}
function jp(){if(M("use_new_nwl"))return Xo();fp||(fp=new To({Oc:!0,Ec:!0}));return fp}
function pp(a,b,c){c&&0===Object.keys(b).length?Ko(a):ol(a,b)}
function op(){return B("ytNetworklessLoggingInitializationOptions")?gp.isNwlInitialized:cp}
function up(){return B("ytNetworklessLoggingInitializationOptions")?gp.potentialEsfErrorCounter:ep}
;function Hp(a){var b=this;this.config_=null;a?this.config_=a:Nl()&&(this.config_=Ol());fm(function(){cm(b)},0,5E3)}
Hp.prototype.isReady=function(){!this.config_&&Nl()&&(this.config_=Ol());return!!this.config_};
function dm(a,b,c,d){function e(A){A=void 0===A?!1:A;var E;if(d.retry&&"www.youtube-nocookie.com"!=h&&(A||M("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(E=am(b,c,m,k)),E)){var F=g.onSuccess,N=g.onFetchSuccess;g.onSuccess=function(O,R){bm(E);F(O,R)};
c.onFetchSuccess=function(O,R){bm(E);N(O,R)}}try{A&&d.retry&&!d.Xb.bypassNetworkless?(g.method="POST",d.Xb.writeThenSend?M("use_new_nwl_wts")?$o().writeThenSend(u,g):np(u,g):M("use_new_nwl_saw")?$o().sendAndWrite(u,g):rp(u,g)):(g.method="POST",g.postParams||(g.postParams={}),ol(u,g))}catch(O){if("InvalidAccessError"==O.name)E&&(bm(E),E=0),Pk(Error("An extension is blocking network request."));
else throw O;}E&&fm(function(){cm(a)},0,5E3)}
!L("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Pk(new Q("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new Q("innertube xhrclient not ready",b,c,d);Ok(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(A,E){if(d.onSuccess)d.onSuccess(E)},
onFetchSuccess:function(A){if(d.onSuccess)d.onSuccess(A)},
onError:function(A,E){if(d.onError)d.onError(E)},
onFetchError:function(A){if(d.onError)d.onError(A)},
timeout:d.timeout,withCredentials:!0};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.Lc)&&(h=f);var k=a.config_.Nc||!1,m=Vl(k,h,d);Object.assign(g.headers,m);(f=g.headers.Authorization)&&!h&&(g.headers["x-origin"]=window.location.origin);var q="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,r={alt:"json"},w=a.config_.Mc&&f;w=w&&f.startsWith("Bearer");w||(r.key=a.config_.innertubeApiKey);var u=al(""+h+q,r||{},!0);M("use_new_nwl")&&$o().i||!M("use_new_nwl")&&
op()?Fn().then(function(A){e(A)}):e(!1)}
;var fq=0,gq=Pc?"webkit":Oc?"moz":Mc?"ms":Lc?"o":"";z("ytDomDomGetNextId",B("ytDomDomGetNextId")||function(){return++fq});var hq={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function iq(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in hq||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.i=a.pageX;this.j=a.pageY}}catch(e){}}
function jq(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.i=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.j=a.clientY+b}}
iq.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
iq.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
iq.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var qb=y.ytEventsEventsListeners||{};z("ytEventsEventsListeners",qb);var kq=y.ytEventsEventsCounter||{count:0};z("ytEventsEventsCounter",kq);
function lq(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return pb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Qa(e[4])&&Qa(d)&&ub(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var mq=db(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function nq(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=lq(a,b,c,d);if(e)return e;e=++kq.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new iq(h);if(!lf(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new iq(h);
h.currentTarget=a;return c.call(a,h)};
g=Nk(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),mq()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);qb[e]=[a,b,c,g,d];return e}
function oq(a){a&&("string"==typeof a&&(a=[a]),fb(a,function(b){if(b in qb){var c=qb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?mq()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete qb[b]}}))}
;var pq=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function qq(a){this.G=a;this.j=null;this.o=0;this.v=null;this.s=0;this.l=[];for(a=0;4>a;a++)this.l.push(0);this.m=0;this.K=nq(window,"mousemove",Wa(this.P,this));a=Wa(this.J,this);"function"===typeof a&&(a=Nk(a));this.R=window.setInterval(a,25)}
Za(qq,J);qq.prototype.P=function(a){void 0===a.i&&jq(a);var b=a.i;void 0===a.j&&jq(a);this.j=new gf(b,a.j)};
qq.prototype.J=function(){if(this.j){var a=pq();if(0!=this.o){var b=this.v,c=this.j,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.o);this.l[this.m]=.5<Math.abs((d-this.s)/this.s)?1:0;for(c=b=0;4>c;c++)b+=this.l[c]||0;3<=b&&this.G();this.s=d}this.o=a;this.v=this.j;this.m=(this.m+1)%4}};
qq.prototype.C=function(){window.clearInterval(this.R);oq(this.K)};var rq={};
function sq(a){var b=void 0===a?{}:a;a=void 0===b.Tc?!1:b.Tc;b=void 0===b.Fc?!0:b.Fc;if(null==B("_lact",window)){var c=parseInt(L("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;z("_lact",c,window);z("_fact",c,window);-1==c&&tq();nq(document,"keydown",tq);nq(document,"keyup",tq);nq(document,"mousedown",tq);nq(document,"mouseup",tq);a?nq(window,"touchmove",function(){uq("touchmove",200)},{passive:!0}):(nq(window,"resize",function(){uq("resize",200)}),b&&nq(window,"scroll",function(){uq("scroll",200)}));
new qq(function(){uq("mouse",100)});
nq(document,"touchstart",tq,{passive:!0});nq(document,"touchend",tq,{passive:!0})}}
function uq(a,b){rq[a]||(rq[a]=!0,Xh.S(function(){tq();rq[a]=!1},b))}
function tq(){null==B("_lact",window)&&sq();var a=Date.now();z("_lact",a,window);-1==B("_fact",window)&&z("_fact",a,window);(a=B("ytglobal.ytUtilActivityCallback_"))&&a()}
function vq(){var a=B("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var wq=y.ytPubsubPubsubInstance||new K,xq=y.ytPubsubPubsubSubscribedKeys||{},yq=y.ytPubsubPubsubTopicToKeys||{},zq=y.ytPubsubPubsubIsSynchronous||{};function Aq(a,b){var c=Bq();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){xq[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{zq[a]?f():hl(f,0)}catch(g){Ok(g)}},void 0);
xq[d]=!0;yq[a]||(yq[a]=[]);yq[a].push(d);return d}return 0}
function Cq(a){var b=Bq();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),fb(a,function(c){b.unsubscribeByKey(c);delete xq[c]}))}
function Dq(a,b){var c=Bq();c&&c.publish.apply(c,arguments)}
function Eq(a){var b=Bq();if(b)if(b.clear(a),a)Fq(a);else for(var c in yq)Fq(c)}
function Bq(){return y.ytPubsubPubsubInstance}
function Fq(a){yq[a]&&(a=yq[a],fb(a,function(b){xq[b]&&delete xq[b]}),a.length=0)}
K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.Da;K.prototype.publish=K.prototype.qa;K.prototype.clear=K.prototype.clear;z("ytPubsubPubsubInstance",wq);z("ytPubsubPubsubTopicToKeys",yq);z("ytPubsubPubsubIsSynchronous",zq);z("ytPubsubPubsubSubscribedKeys",xq);function Gq(a){this.policy=a;this.store=[];this.i={}}
Gq.prototype.storePayload=function(a,b){this.store.push({payload:b,keys:a});b=[void 0===a.auth?"undefined":a.auth,void 0===a.isJspb?"undefined":a.isJspb,void 0===a.isLeader?"undefined":a.isLeader,void 0===a.cttAuthInfo?"undefined":a.cttAuthInfo].join("/");this.i[b]?this.i[b]++:this.i[b]=1;this.i[b]>=this.policy.maxBatchSize&&(this.policy.onBatchSizeExceeded(a),this.i[b]=0);return b};
Gq.prototype.extractMatchingEntries=function(a){for(var b=[],c=[],d=p(this.store),e=d.next();!e.done;e=d.next()){e=e.value;a:{var f=a;var g=Object.keys(f);g=p(g);for(var h=g.next();!h.done;h=g.next())if(h=h.value,e.keys[h]!==f[h]){f=!1;break a}f=!0}f?b.push(e.payload):c.push(e)}this.store=c;c=0;a=Hq(this,a);a=p(a);for(d=a.next();!d.done;d=a.next())d=d.value,c+=this.i[d],this.i[d]=0;c!==b.length&&Pk(new Q("Transport IMS extracted entries count != keyCounter sum",b.length,c));return b};
Gq.prototype.getSequenceCount=function(a){var b=Hq(this,a);a=0;b=p(b);for(var c=b.next();!c.done;c=b.next())a+=this.i[c.value];return a};
function Hq(a,b){var c=Object.keys(b),d="THIS_KEY_FIELD_NOT_FILLED",e="THIS_KEY_FIELD_NOT_FILLED",f="THIS_KEY_FIELD_NOT_FILLED",g="THIS_KEY_FIELD_NOT_FILLED";c=p(c);for(var h=c.next();!h.done;h=c.next())h=h.value,"auth"===h?d=Iq(b.auth):"isJspb"===h?e=JSON.stringify(b.isJspb):"isLeader"===h?f=JSON.stringify(b.isLeader):"cttAuthInfo"===h&&(g=Iq(b.cttAuthInfo));b=[];d=[d,e,f,g];a=p(Object.keys(a.i));for(e=a.next();!e.done;e=a.next()){e=e.value;f=e.split("/");g=!0;for(c=0;c<d.length;c++)if("THIS_KEY_FIELD_NOT_FILLED"!==
d[c]&&d[c]!==f[c]){g=!1;break}g&&b.push(e)}return b}
Gq.prototype.getSequenceCount=Gq.prototype.getSequenceCount;Gq.prototype.extractMatchingEntries=Gq.prototype.extractMatchingEntries;Gq.prototype.storePayload=Gq.prototype.storePayload;function Iq(a){return void 0===a?"undefined":a}
;var Jq=y.window;Jq.ytExports||(Jq.ytExports={logging:{transport:{leaderQueueLength:0,leaderChosen:!1}}});var Kq=Ik("initial_gel_batch_timeout",2E3),Lq=Math.pow(2,16)-1,Mq=!1,Nq=void 0;function Oq(){this.l=this.i=this.j=0}
var Pq=new Oq,Qq=new Oq,Rq=!0,Sq=y.ytLoggingTransportGELQueue_||new Map;z("ytLoggingTransportGELQueue_",Sq);var Tq=new Map,Uq=y.ytLoggingTransportGELProtoQueue_||new Map;z("ytLoggingTransportGELProtoQueue_",Uq);var Vq=y.ytLoggingTransportTokensToCttTargetIds_||{};z("ytLoggingTransportTokensToCttTargetIds_",Vq);var Wq=y.ytLoggingTransportTokensToJspbCttTargetIds_||{};z("ytLoggingTransportTokensToJspbCttTargetIds_",Wq);var Xq={};
function Yq(){var a=B("yt.logging.ims");a||(a=new Gq({maxBatchSize:Ik("tvhtml5_logging_max_batch")||Ik("web_logging_max_batch")||100,onBatchSizeExceeded:function(b){Zq({writeThenSend:!0},void 0,b.isJspb)}}),z("yt.logging.ims",a));
return a}
function $q(){M("jspb_with_transport_leader")&&!Jq.ytExports.logging.transport.leaderChosen&&(Mq=Jq.ytExports.logging.transport.leaderChosen=!0,document.addEventListener("FLUSH_REQUEST",function(){Zq(void 0,void 0,!0)}))}
function ar(a,b){$q();if("log_event"===a.endpoint){br(a);var c=cr(a);if(M("use_new_in_memory_storage")){Xq[c]=!0;var d={cttAuthInfo:c,isJspb:!1,isLeader:Mq};Yq().storePayload(d,a.payload);dr(b,[],c,!1,d)}else d=Sq.get(c)||[],Sq.set(c,d),d.push(a.payload),dr(b,d,c)}}
function er(a,b){$q();if("log_event"===a.endpoint){br(void 0,a);var c=cr(a,!0);if(M("jspb_with_transport_leader")&&Mq)if(M("use_new_in_memory_storage")){Xq[c]=!0;var d={cttAuthInfo:c,isJspb:!0,isLeader:Mq};Yq().storePayload(d,a.payload);Jq.ytExports.logging.transport.leaderQueueLength++;dr(b,[],c,!0,d)}else d=Tq.get(c)||[],Tq.set(c,d),Jq.ytExports.logging.transport.leaderQueueLength++,d.push(a.payload),dr(b,d,c,!0);else M("use_new_in_memory_storage")?(Xq[c]=!0,d={cttAuthInfo:c,isJspb:!0,isLeader:Mq},
Yq().storePayload(d,a.payload.toJSON()),dr(b,[],c,!0,d)):(d=Uq.get(c)||[],Uq.set(c,d),a=a.payload.toJSON(),d.push(a),dr(b,d,c,!0))}}
function dr(a,b,c,d,e){d=void 0===d?!1:d;a&&(Nq=new a);a=Ik("tvhtml5_logging_max_batch")||Ik("web_logging_max_batch")||100;var f=P(),g=d?Qq.l:Pq.l,h=Uq.get(c)||[];b=b.length;e&&(e=vb(e),delete e.isLeader,b=Yq().getSequenceCount(e));M("jspb_with_transport_leader")&&(Mq&&b+h.length>=a||!Mq&&Jq.ytExports.logging.transport.leaderQueueLength+b>=a)||b>=a?Zq({writeThenSend:!0},M("flush_only_full_queue")?c:void 0,d):10<=f-g&&(fr(d),d?Qq.l=f:Pq.l=f)}
function gr(a,b){$q();if("log_event"===a.endpoint){br(a);var c=cr(a),d=new Map;d.set(c,[a.payload]);b&&(Nq=new b);return new yf(function(e,f){Nq&&Nq.isReady()?hr(d,Nq,e,f,{bypassNetworkless:!0},!0):e()})}}
function ir(a,b){$q();if("log_event"===a.endpoint){br(void 0,a);var c=cr(a,!0),d=new Map,e=new Map;M("jspb_with_transport_leader")&&Mq?e.set(c,[a.payload]):d.set(c,[a.payload.toJSON()]);b&&(Nq=new b);return new yf(function(f){Nq&&Nq.isReady()?jr(d,e,Nq,f,{bypassNetworkless:!0},!0):f()})}}
function cr(a,b){var c="";if(a.Fa)c="visitorOnlyApprovedKey";else if(a.cttAuthInfo){if(void 0===b?0:b){b=a.cttAuthInfo.token;c=a.cttAuthInfo;var d=new rk;c.videoId?d.setVideoId(c.videoId):c.playlistId&&Ud(d,2,sk,c.playlistId);Wq[b]=d}else b=a.cttAuthInfo,c={},b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId),Vq[a.cttAuthInfo.token]=c;c=a.cttAuthInfo.token}return c}
function Zq(a,b,c){a=void 0===a?{}:a;c=void 0===c?!1:c;new yf(function(d,e){c?(il(Qq.j),il(Qq.i),Qq.i=0):(il(Pq.j),il(Pq.i),Pq.i=0);if(M("jspb_with_transport_leader")&&!Mq&&c)document.dispatchEvent(new CustomEvent("FLUSH_REQUEST")),d();else if(Nq&&Nq.isReady())if(M("use_new_in_memory_storage"))a:{var f=a,g=c,h=Nq;f=void 0===f?{}:f;g=void 0===g?!1:g;var k=new Map,m=new Map,q=new Map;if(void 0!==b){if(g){e=Yq().extractMatchingEntries({isJspb:g,cttAuthInfo:b,isLeader:!1});k.set(b,e);if(M("jspb_with_transport_leader")){e=
Yq().extractMatchingEntries({isJspb:!0,cttAuthInfo:b,isLeader:!0});if(0===e.length)break a;m.set(b,e)}jr(k,m,h,d,f)}}else if(g){e=p(Object.keys(Xq));for(g=e.next();!g.done;g=e.next())q=g.value,g=Yq().extractMatchingEntries({isJspb:!0,isLeader:!1,cttAuthInfo:q}),0<g.length&&k.set(q,g),M("jspb_with_transport_leader")&&(g=Yq().extractMatchingEntries({isJspb:!0,isLeader:!0,cttAuthInfo:q}),0<g.length&&m.set(q,g)),Xq[q]=!1;jr(k,m,h,d,f)}else{k=p(Object.keys(Xq));for(g=k.next();!g.done;g=k.next())m=g.value,
g=Yq().extractMatchingEntries({isJspb:!1,cttAuthInfo:m}),0!==g.length&&q.set(m,g);hr(q,h,d,e,f)}}else f=a,k=c,h=Nq,f=void 0===f?{}:f,k=void 0===k?!1:k,void 0!==b?k?(e=new Map,k=new Map,m=Uq.get(b)||[],e.set(b,m),M("jspb_with_transport_leader")&&(m=Tq.get(b)||[],k.set(b,m)),jr(e,k,h,d,f),M("jspb_with_transport_leader")&&Tq.delete(b),Uq.delete(b)):(k=new Map,m=Sq.get(b)||[],k.set(b,m),hr(k,h,d,e,f),Sq.delete(b)):k?(jr(Uq,Tq,h,d,f),Uq.clear(),M("jspb_with_transport_leader")&&Tq.clear()):(hr(Sq,h,d,e,
f),Sq.clear());else fr(c),d()})}
function fr(a){a=void 0===a?!1:a;if(M("web_gel_timeout_cap")&&(!a&&!Pq.i||a&&!Qq.i)){var b=hl(function(){Zq({writeThenSend:!0},void 0,a)},6E4);
a?Qq.i=b:Pq.i=b}il(a?Qq.j:Pq.j);b=L("LOGGING_BATCH_TIMEOUT",Ik("web_gel_debounce_ms",1E4));M("shorten_initial_gel_batch_timeout")&&Rq&&(b=Kq);b=hl(function(){Zq({writeThenSend:!0},void 0,a)},b);
a?Qq.j=b:Pq.j=b}
function hr(a,b,c,d,e,f){e=void 0===e?{}:e;var g=Math.round(P()),h=a.size;a=p(a);for(var k=a.next();!k.done;k=a.next()){var m=p(k.value);k=m.next().value;var q=m.next().value;m=k;k=wb({context:Pl(b.config_||Ol())});if(!Pa(q)&&!M("throw_err_when_logevent_malformed_killswitch")){Ok(new Q("LogEvent value at event was not an array",q));d();break}k.events=q;(q=Vq[m])&&kr(k,m,q);delete Vq[m];m="visitorOnlyApprovedKey"===m;lr(k,g,m);mr(e);q=function(){h--;h||c()};
var r=function(){h--;h||c()};
try{dm(b,"log_event",k,nr(e,m,q,r,f)),Rq=!1}catch(w){Ok(w),d()}}}
function jr(a,b,c,d,e,f){e=void 0===e?{}:e;var g=Math.round(P()),h=a.size+b.size,k=new Map([].concat(ha(a),ha(b)));k=p(k);for(var m=k.next();!m.done;m=k.next()){var q=p(m.value).next().value,r=a.get(q),w=b.get(q)||[];m=new tk;var u=Ul(c.config_||Ol());G(m,$i,1,u);r=r?or(r):[];r=p(r);for(u=r.next();!u.done;u=r.next())ae(m,3,Uj,u.value);w=p(w);for(r=w.next();!r.done;r=w.next())ae(m,3,Uj,r.value);(w=Wq[q])&&pr(m,q,w);delete Wq[q];q="visitorOnlyApprovedKey"===q;qr(m,g,q);mr(e);m=de(m);q=nr(e,q,function(){Jq.ytExports.logging.transport.leaderQueueLength=
0;h--;h||d()},function(){Jq.ytExports.logging.transport.leaderQueueLength=0;
h--;h||d()},f);
q.headers["Content-Type"]="application/json+protobuf";q.postBodyFormat="JSPB";q.postBody=m;dm(c,"log_event","",q);Rq=!1}}
function mr(a){M("always_send_and_write")&&(a.writeThenSend=!1)}
function nr(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,Xb:a,Fa:b,tq:!!e,headers:{},postBodyFormat:"",postBody:""};M("use_request_time_ms_header")&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(P())));return a}
function lr(a,b,c){a.requestTimeMs=String(b);M("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=L("EVENT_ID"))&&(c=rr(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function qr(a,b,c){D(a,2,b);if(!c&&(b=L("EVENT_ID"))){c=rr();var d=new qk;D(d,1,b);D(d,2,c);G(a,qk,5,d)}}
function rr(){var a=L("BATCH_CLIENT_COUNTER")||0;a||(a=Math.floor(Math.random()*Lq/2));a++;a>Lq&&(a=1);Fk("BATCH_CLIENT_COUNTER",a);return a}
function kr(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function pr(a,b,c){if(Qd(c,1===Vd(c,sk)?1:-1))var d=1;else if(c.getPlaylistId())d=2;else return;G(a,rk,4,c);a=Wd(a,$i,1)||new $i;c=Wd(a,Yi,3)||new Yi;var e=new Xi;e.setToken(b);D(e,1,d);ae(c,12,Xi,e);G(a,Yi,3,c)}
function or(a){for(var b=[],c=0;c<a.length;c++)try{b.push(new Uj(a[c]))}catch(d){Ok(new Q("Transport failed to deserialize "+String(a[c])))}return b}
function br(a,b){if(B("yt.logging.transport.enableScrapingForTest")){var c=B("yt.logging.transport.scrapedPayloadsForTesting"),d=B("yt.logging.transport.payloadToScrape","");b&&(b=B("yt.logging.transport.getScrapedPayloadFromClientEventsFunction").bind(b.payload)())&&c.push(b);a&&a.payload[d]&&c.push((null==a?void 0:a.payload)[d]);z("yt.logging.transport.scrapedPayloadsForTesting",c)}}
;var sr=y.ytLoggingGelSequenceIdObj_||{};z("ytLoggingGelSequenceIdObj_",sr);function tr(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||P());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=vq();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};M("log_sequence_info_on_gel_web")&&d.ba&&(a=e.context,b=d.ba,b={index:ur(b),groupKey:b},a.sequence=b,d.Pb&&delete sr[d.ba]);(d.hc?gr:ar)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,Fa:d.Fa},c)}
function vr(a){Zq(void 0,void 0,void 0===a?!1:a)}
function ur(a){sr[a]=a in sr?sr[a]+1:0;return sr[a]}
;var wr=y.ytLoggingGelSequenceIdObj_||{};z("ytLoggingGelSequenceIdObj_",wr);function xr(a,b,c){c=void 0===c?{}:c;var d=Math.round(c.timestamp||P());D(a,1,d<Number.MAX_SAFE_INTEGER?d:0);var e=vq();d=new Tj;D(d,1,c.timestamp||!isFinite(e)?-1:e);if(M("log_sequence_info_on_gel_web")&&c.ba){e=c.ba;var f=ur(e),g=new Sj;D(g,2,f);D(g,1,e);G(d,Sj,3,g);c.Pb&&delete wr[c.ba]}G(a,Tj,33,d);(c.hc?ir:er)({endpoint:"log_event",payload:a,cttAuthInfo:c.cttAuthInfo,Fa:c.Fa},b)}
;function yr(a,b){b=void 0===b?{}:b;var c=!1;L("ytLoggingEventsDefaultDisabled",!1)&&(c=!0);xr(a,c?null:Hp,b)}
;function zr(a,b){var c=new Uj;Zd(c,Hj,72,Vj,a);yr(c,b)}
function Ar(a,b,c){var d=new Uj;Zd(d,Gj,73,Vj,a);c?xr(d,c,b):yr(d,b)}
function Br(a,b,c){var d=new Uj;Zd(d,Fj,78,Vj,a);c?xr(d,c,b):yr(d,b)}
function Cr(a,b,c){var d=new Uj;Zd(d,Ij,208,Vj,a);c?xr(d,c,b):yr(d,b)}
function Dr(a,b,c){var d=new Uj;Zd(d,yj,156,Vj,a);c?xr(d,c,b):yr(d,b)}
function Er(a,b,c){var d=new Uj;Zd(d,Cj,215,Vj,a);c?xr(d,c,b):yr(d,b)}
function Fr(a,b,c){var d=new Uj;Zd(d,uj,111,Vj,a);c?xr(d,c,b):yr(d,b)}
;function um(a,b,c){c=void 0===c?{}:c;if(M("migrate_events_to_ts")){c=void 0===c?{}:c;var d=Hp;L("ytLoggingEventsDefaultDisabled",!1)&&Hp===Hp&&(d=null);tr(a,b,d,c)}else d=Hp,L("ytLoggingEventsDefaultDisabled",!1)&&Hp==Hp&&(d=null),tr(a,b,d,c)}
;var Gr=[{ub:function(a){return"Cannot read property '"+a.key+"'"},
bb:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{ub:function(a){return"Cannot call '"+a.key+"'"},
bb:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{ub:function(a){return a.key+" is not defined"},
bb:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Ir={na:[],ma:[{callback:Hr,weight:500}]};function Hr(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Jr(){this.ma=[];this.na=[]}
var Kr;function Lr(){if(!Kr){var a=Kr=new Jr;a.na.length=0;a.ma.length=0;Ir.na&&a.na.push.apply(a.na,Ir.na);Ir.ma&&a.ma.push.apply(a.ma,Ir.ma)}return Kr}
;var Mr=new K;function Nr(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Or(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=Or(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=Or(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function Or(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function Pr(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Qr(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=Nr(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?Qr(e+".ve",f,g,h):0;d+=g;d+=Qr(e,a[e],b,c);if(500<d)break}}else c[b]=Rr(a),d+=c[b].length;else c[b]=Rr(a),d+=c[b].length;return d}
function Qr(a,b,c,d){c+="."+a;a=Rr(b);d[c]=a;return c.length+a.length}
function Rr(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;var Sr=new Set,Tr=0,Ur=0,Vr=0,Wr=[],Xr=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function tm(a){Yr(a)}
function Zr(a){Yr(a,"WARNING")}
function Yr(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||L("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||L("INNERTUBE_CONTEXT_CLIENT_VERSION");var g=f||{},h=void 0===b?"ERROR":b;h=void 0===h?"ERROR":h;if(a){a.hasOwnProperty("level")&&a.level&&(h=a.level);if(M("console_log_js_exceptions")){var k=[];k.push("Name: "+a.name);k.push("Message: "+a.message);a.hasOwnProperty("params")&&k.push("Error Params: "+JSON.stringify(a.params));a.hasOwnProperty("args")&&k.push("Error args: "+JSON.stringify(a.args));
k.push("File name: "+a.fileName);k.push("Stacktrace: "+a.stack);window.console.log(k.join("\n"),a)}if(!(5<=Tr)){var m=Wr,q=ue(a),r=q.message||"Unknown Error",w=q.name||"UnknownError",u=q.stack||a.j||"Not available";if(u.startsWith(w+": "+r)){var A=u.split("\n");A.shift();u=A.join("\n")}var E=q.lineNumber||"Not available",F=q.fileName||"Not available",N=u,O=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var R=0;R<a.args.length&&!(O=Pr(a.args[R],"params."+R,g,O),500<=O);R++);else if(a.hasOwnProperty("params")&&
a.params){var U=a.params;if("object"===typeof a.params)for(var ca in U){if(U[ca]){var lb="params."+ca,Xa=Rr(U[ca]);g[lb]=Xa;O+=lb.length+Xa.length;if(500<O)break}}else g.params=Rr(U)}if(m.length)for(var ja=0;ja<m.length&&!(O=Pr(m[ja],"params.context."+ja,g,O),500<=O);ja++);navigator.vendor&&!g.hasOwnProperty("vendor")&&(g["device.vendor"]=navigator.vendor);var H={message:r,name:w,lineNumber:E,fileName:F,stack:N,params:g,sampleWeight:1},ka=Number(a.columnNumber);isNaN(ka)||(H.lineNumber=H.lineNumber+
":"+ka);if("IGNORED"===a.level)var ma=0;else a:{for(var Fe=Lr(),Ge=p(Fe.na),wd=Ge.next();!wd.done;wd=Ge.next()){var xd=wd.value;if(H.message&&H.message.match(xd.Cq)){ma=xd.weight;break a}}for(var yd=p(Fe.ma),va=yd.next();!va.done;va=yd.next()){var vp=va.value;if(vp.callback(H)){ma=vp.weight;break a}}ma=1}H.sampleWeight=ma;for(var wp=p(Gr),Xj=wp.next();!Xj.done;Xj=wp.next()){var Yj=Xj.value;if(Yj.bb[H.name])for(var xp=p(Yj.bb[H.name]),Zj=xp.next();!Zj.done;Zj=xp.next()){var yp=Zj.value,Ug=H.message.match(yp.regexp);
if(Ug){H.params["params.error.original"]=Ug[0];for(var ak=yp.groups,zp={},zd=0;zd<ak.length;zd++)zp[ak[zd]]=Ug[zd+1],H.params["params.error."+ak[zd]]=Ug[zd+1];H.message=Yj.ub(zp);break}}}H.params||(H.params={});var Ap=Lr();H.params["params.errorServiceSignature"]="msg="+Ap.na.length+"&cb="+Ap.ma.length;H.params["params.serviceWorker"]="false";y.document&&y.document.querySelectorAll&&(H.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));Db("sample").constructor!==
Bb&&(H.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(H);if(0!==H.sampleWeight&&!Sr.has(H.message)){if("ERROR"===h){Mr.qa("handleError",H);if(M("record_app_crashed_web")&&0===Vr&&1===H.sampleWeight)if(Vr++,M("errors_via_jspb")){var bk=new rj;D(bk,1,1);if(!M("report_client_error_with_app_crash_ks")){var Bp=new mj;D(Bp,1,H.message);var Cp=new nj;G(Cp,mj,3,Bp);var Dp=new oj;G(Dp,nj,5,Cp);var Ep=new pj;G(Ep,oj,9,Dp);G(bk,pj,4,Ep)}var Fp=new Uj;Zd(Fp,rj,20,
Vj,bk);yr(Fp)}else{var Gp={appCrashType:"APP_CRASH_TYPE_BREAKPAD"};M("report_client_error_with_app_crash_ks")||(Gp.systemHealth={crashData:{clientError:{logMessage:{message:H.message}}}});um("appCrashed",Gp)}Ur++}else"WARNING"===h&&Mr.qa("handleWarning",H);if(M("kevlar_gel_error_routing"))a:{var He=h;if(M("errors_via_jspb")){if($r())var Ip=void 0;else{var Ad=new jj;D(Ad,1,H.stack);H.fileName&&D(Ad,4,H.fileName);var Jb=H.lineNumber&&H.lineNumber.split?H.lineNumber.split(":"):[];0!==Jb.length&&(1!==
Jb.length||isNaN(Number(Jb[0]))?2!==Jb.length||isNaN(Number(Jb[0]))||isNaN(Number(Jb[1]))||(D(Ad,2,Number(Jb[0])),D(Ad,3,Number(Jb[1]))):D(Ad,2,Number(Jb[0])));var Ac=new mj;D(Ac,1,H.message);D(Ac,3,H.name);D(Ac,6,H.sampleWeight);"ERROR"===He?D(Ac,2,2):"WARNING"===He?D(Ac,2,1):D(Ac,2,0);var ck=new kj;D(ck,1,!0);Zd(ck,jj,3,lj,Ad);var cc=new gj;D(cc,3,window.location.href);for(var Jp=L("FEXP_EXPERIMENTS",[]),dk=0;dk<Jp.length;dk++){var Pv=Jp[dk];Dd(cc);Rd(cc,5).push(Pv)}var ek=L("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");
if(!Gk()&&ek)for(var Kp=p(Object.keys(ek)),Bc=Kp.next();!Bc.done;Bc=Kp.next()){var Lp=Bc.value,fk=new ij;D(fk,1,Lp);fk.setValue(String(ek[Lp]));ae(cc,4,ij,fk)}var gk=H.params;if(gk){var Mp=p(Object.keys(gk));for(Bc=Mp.next();!Bc.done;Bc=Mp.next()){var Np=Bc.value,hk=new ij;D(hk,1,"client."+Np);hk.setValue(String(gk[Np]));ae(cc,4,ij,hk)}}var Op=L("SERVER_NAME"),Pp=L("SERVER_VERSION");if(Op&&Pp){var ik=new ij;D(ik,1,"server.name");ik.setValue(Op);ae(cc,4,ij,ik);var jk=new ij;D(jk,1,"server.version");
jk.setValue(Pp);ae(cc,4,ij,jk)}var Vg=new nj;G(Vg,gj,1,cc);G(Vg,kj,2,ck);G(Vg,mj,3,Ac);Ip=Vg}var Qp=Ip;if(!Qp)break a;var Rp=new Uj;Zd(Rp,nj,163,Vj,Qp);yr(Rp)}else{if($r())var Sp=void 0;else{var Ie={stackTrace:H.stack};H.fileName&&(Ie.filename=H.fileName);var Kb=H.lineNumber&&H.lineNumber.split?H.lineNumber.split(":"):[];0!==Kb.length&&(1!==Kb.length||isNaN(Number(Kb[0]))?2!==Kb.length||isNaN(Number(Kb[0]))||isNaN(Number(Kb[1]))||(Ie.lineNumber=Number(Kb[0]),Ie.columnNumber=Number(Kb[1])):Ie.lineNumber=
Number(Kb[0]));var kk={level:"ERROR_LEVEL_UNKNOWN",message:H.message,errorClassName:H.name,sampleWeight:H.sampleWeight};"ERROR"===He?kk.level="ERROR_LEVEL_ERROR":"WARNING"===He&&(kk.level="ERROR_LEVEL_WARNNING");var Qv={isObfuscated:!0,browserStackInfo:Ie},Bd={pageUrl:window.location.href,kvPairs:[]};L("FEXP_EXPERIMENTS")&&(Bd.experimentIds=L("FEXP_EXPERIMENTS"));var lk=L("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!Gk()&&lk)for(var Tp=p(Object.keys(lk)),Cc=Tp.next();!Cc.done;Cc=Tp.next()){var Up=
Cc.value;Bd.kvPairs.push({key:Up,value:String(lk[Up])})}var mk=H.params;if(mk){var Vp=p(Object.keys(mk));for(Cc=Vp.next();!Cc.done;Cc=Vp.next()){var Wp=Cc.value;Bd.kvPairs.push({key:"client."+Wp,value:String(mk[Wp])})}}var Xp=L("SERVER_NAME"),Yp=L("SERVER_VERSION");Xp&&Yp&&(Bd.kvPairs.push({key:"server.name",value:Xp}),Bd.kvPairs.push({key:"server.version",value:Yp}));Sp={errorMetadata:Bd,stackTrace:Qv,logMessage:kk}}var Zp=Sp;if(!Zp)break a;um("clientError",Zp)}if("ERROR"===He||M("errors_flush_gel_always_killswitch"))b:if(M("migrate_events_to_ts"))c:{if(M("web_fp_via_jspb")&&
(vr(!0),!M("web_fp_via_jspb_and_json")))break c;vr()}else{if(M("web_fp_via_jspb")&&(vr(!0),!M("web_fp_via_jspb_and_json")))break b;vr()}}if(!M("suppress_error_204_logging")){var Je=H.params||{},dc={urlParams:{a:"logerror",t:"jserror",type:H.name,msg:H.message.substr(0,250),line:H.lineNumber,level:h,"client.name":Je.name},postParams:{url:L("PAGE_NAME",window.location.href),file:H.fileName},method:"POST"};Je.version&&(dc["client.version"]=Je.version);if(dc.postParams){H.stack&&(dc.postParams.stack=
H.stack);for(var $p=p(Object.keys(Je)),nk=$p.next();!nk.done;nk=$p.next()){var aq=nk.value;dc.postParams["client."+aq]=Je[aq]}var ok=L("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(ok)for(var bq=p(Object.keys(ok)),pk=bq.next();!pk.done;pk=bq.next()){var cq=pk.value;dc.postParams[cq]=ok[cq]}var dq=L("SERVER_NAME"),eq=L("SERVER_VERSION");dq&&eq&&(dc.postParams["server.name"]=dq,dc.postParams["server.version"]=eq)}ol(L("ECATCHER_REPORT_HOST","")+"/error_204",dc)}try{Sr.add(H.message)}catch(sx){}Tr++}}}}
function $r(){for(var a=p(Xr),b=a.next();!b.done;b=a.next())if(lm(b.value.toLowerCase()))return!0;return!1}
function as(a){var b=Ja.apply(1,arguments);a.args||(a.args=[]);a.args.push.apply(a.args,ha(b))}
;function bs(){this.register=new Map}
function cs(a){a=p(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Fq("ABORTED")}
bs.prototype.clear=function(){cs(this);this.register.clear()};
var ds=new bs;var es=Date.now().toString();
function fs(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(es)for(a=1,b=0;b<es.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^es.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var gs=y.ytLoggingDocDocumentNonce_;gs||(gs=fs(),z("ytLoggingDocDocumentNonce_",gs));var hs=gs;var is={Eh:0,ie:1,se:2,yl:3,Gh:4,Lp:5,nm:6,Un:7,qn:8,In:9,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE",8:"PUSH_NOTIFICATIONS",9:"RICH_GRID_WATCH"};function js(a){this.i=a}
function ks(a){return new js({trackingParams:a})}
js.prototype.getAsJson=function(){var a={};void 0!==this.i.trackingParams?a.trackingParams=this.i.trackingParams:(a.veType=this.i.veType,void 0!==this.i.veCounter&&(a.veCounter=this.i.veCounter),void 0!==this.i.elementIndex&&(a.elementIndex=this.i.elementIndex));void 0!==this.i.dataElement&&(a.dataElement=this.i.dataElement.getAsJson());void 0!==this.i.youtubeData&&(a.youtubeData=this.i.youtubeData);return a};
js.prototype.getAsJspb=function(){var a=new tj;if(void 0!==this.i.trackingParams){var b=this.i.trackingParams;null!=b&&b instanceof kd&&jd();D(a,1,b)}else void 0!==this.i.veType&&D(a,2,this.i.veType),void 0!==this.i.veCounter&&D(a,6,this.i.veCounter),void 0!==this.i.elementIndex&&D(a,3,this.i.elementIndex);void 0!==this.i.dataElement&&(b=this.i.dataElement.getAsJspb(),G(a,tj,7,b));void 0!==this.i.youtubeData&&G(a,Mi,8,this.i.jspbYoutubeData);return a};
js.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
js.prototype.isClientVe=function(){return!this.i.trackingParams&&!!this.i.veType};function ls(a){a=void 0===a?0:a;return 0===a?"client-screen-nonce":"client-screen-nonce."+a}
function ms(a){a=void 0===a?0:a;return 0===a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function ns(a){return L(ms(void 0===a?0:a))}
z("yt_logging_screen.getRootVeType",ns);function os(a){return(a=ns(void 0===a?0:a))?new js({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null}
function ps(){var a=L("csn-to-ctt-auth-info");a||(a={},Fk("csn-to-ctt-auth-info",a));return a}
function qs(a){a=L(ls(void 0===a?0:a));if(!a&&!L("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
z("yt_logging_screen.getCurrentCsn",qs);function rs(a,b,c){var d=ps();(c=qs(c))&&delete d[c];b&&(d[a]=b)}
function ss(a){return ps()[a]}
z("yt_logging_screen.getCttAuthInfo",ss);
function ts(a,b,c,d){c=void 0===c?0:c;if(a!==L(ls(c))||b!==L(ms(c)))if(rs(a,d,c),Fk(ls(c),a),Fk(ms(c),b),b=function(){setTimeout(function(){if(a)if(M("web_time_via_jspb")){var e=new uj;D(e,1,hs);D(e,2,a);M("use_default_heartbeat_client")?Fr(e):Fr(e,void 0,Hp)}else e={clientDocumentNonce:hs,clientScreenNonce:a},M("use_default_heartbeat_client")?um("foregroundHeartbeatScreenAssociated",e):tr("foregroundHeartbeatScreenAssociated",e,Hp)},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()}
z("yt_logging_screen.setCurrentScreen",ts);var us=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};z("yt.msgs_",us);function vs(a){Ak(us,arguments)}
;var ws={he:3611,td:27686,ud:85013,vd:23462,xd:42016,yd:62407,zd:26926,wd:43781,Ad:51236,Bd:79148,Cd:50160,Dd:77504,Pd:153587,Qd:87907,Rd:18630,Sd:54445,Td:80935,Ud:152172,Vd:105675,Wd:150723,Xd:37521,Yd:147285,Zd:47786,ae:98349,be:123695,ce:6827,de:29434,ee:7282,ge:124448,ke:32276,je:76278,le:147868,me:147869,ne:93911,oe:106531,pe:27259,qe:27262,re:27263,te:21759,ue:27107,we:62936,xe:49568,ye:38408,ze:80637,Ae:68727,Be:68728,Ce:80353,De:80356,Ee:74610,Fe:45707,Ge:83962,He:83970,Ie:46713,Je:89711,
Ke:74612,Le:155792,Me:93265,Ne:74611,Oe:131380,Qe:128979,Re:139311,Se:128978,Pe:131391,Te:105350,Ve:139312,We:134800,Ue:131392,Ye:113533,Ze:93252,af:99357,cf:94521,df:114252,ef:113532,ff:94522,bf:94583,gf:88E3,hf:139580,jf:93253,kf:93254,lf:94387,mf:94388,nf:93255,pf:97424,Xe:72502,qf:110111,rf:76019,tf:117092,uf:117093,sf:89431,vf:110466,wf:77240,xf:60508,yf:148123,zf:148124,Af:137401,Bf:137402,Cf:137046,Df:73393,Ef:113534,Ff:92098,Gf:131381,Hf:84517,If:83759,Jf:80357,Kf:86113,Lf:72598,Mf:72733,
Nf:107349,Of:124275,Pf:118203,Qf:133275,Rf:152569,Sf:156651,Tf:133274,Uf:133272,Vf:133273,Wf:133276,Xf:144507,Yf:143247,Zf:156652,ag:143248,cg:143249,dg:143250,eg:143251,fg:156653,gg:144401,ig:117431,hg:133797,jg:153964,kg:128572,lg:133405,mg:117429,ng:117430,og:117432,pg:120080,qg:117259,rg:156655,sg:156654,tg:121692,ug:145656,vg:156656,wg:145655,xg:145653,yg:145654,zg:145657,Ag:132972,Bg:133051,Cg:133658,Dg:132971,Eg:97615,Gg:143359,Fg:143356,Ig:143361,Hg:143358,Kg:143360,Jg:143357,Lg:142303,Mg:143353,
Ng:143354,Og:144479,Pg:143355,Qg:31402,Sg:133624,Tg:146477,Ug:133623,Vg:133622,Rg:133621,Wg:84774,Xg:95117,Yg:150497,Zg:98930,ah:98931,bh:98932,dh:43347,eh:129889,fh:149123,gh:45474,hh:100352,ih:84758,jh:98443,kh:117985,lh:74613,mh:155911,nh:74614,oh:64502,ph:136032,qh:74615,rh:74616,sh:122224,th:74617,uh:77820,vh:74618,wh:93278,xh:93274,yh:93275,zh:93276,Ah:22110,Bh:29433,Ch:133798,Dh:132295,Fh:120541,Hh:82047,Ih:113550,Jh:75836,Kh:75837,Lh:42352,Mh:84512,Nh:76065,Oh:75989,Th:16623,Uh:32594,Vh:27240,
Wh:32633,Xh:74858,Yh:156999,ai:3945,Zh:16989,bi:45520,ci:25488,di:25492,fi:25494,gi:55760,hi:14057,ii:18451,ji:57204,ki:57203,li:17897,mi:57205,ni:18198,oi:17898,ri:17909,si:43980,ti:46220,vi:11721,wi:147994,xi:49954,yi:96369,zi:3854,Ai:151633,Bi:56251,Ci:25624,Di:152036,Ui:16906,Vi:99999,Wi:68172,Xi:27068,Yi:47973,Zi:72773,aj:26970,bj:26971,cj:96805,dj:17752,ej:73233,fj:109512,gj:22256,hj:14115,ij:22696,jj:89278,kj:89277,lj:109513,mj:43278,nj:43459,oj:43464,pj:89279,qj:43717,rj:55764,sj:22255,tj:147912,
uj:89281,vj:40963,wj:43277,xj:43442,yj:91824,zj:120137,Aj:96367,Bj:36850,Cj:72694,Dj:37414,Ej:36851,Gj:124863,Fj:121343,Hj:73491,Ij:54473,Jj:43375,Kj:46674,Lj:143815,Mj:139095,Nj:144402,Oj:149968,Pj:149969,Qj:32473,Rj:72901,Sj:72906,Tj:50947,Uj:50612,Vj:50613,Wj:50942,Xj:84938,Yj:84943,Zj:84939,ak:84941,bk:84944,ck:84940,dk:84942,ek:35585,fk:51926,gk:79983,hk:63238,ik:18921,jk:63241,kk:57893,lk:41182,mk:135732,nk:33424,pk:22207,qk:42993,rk:36229,sk:22206,tk:22205,uk:18993,vk:19001,wk:18990,xk:18991,
yk:18997,zk:18725,Ak:19003,Bk:36874,Ck:44763,Dk:33427,Ek:67793,Fk:22182,Gk:37091,Hk:34650,Ik:50617,Jk:47261,Kk:22287,Lk:25144,Mk:97917,Nk:62397,Ok:150871,Pk:150874,Qk:125598,Rk:137935,Sk:36961,Tk:108035,Uk:27426,Vk:27857,Wk:27846,Xk:27854,Yk:69692,Zk:61411,al:39299,bl:38696,dl:62520,fl:36382,il:108701,jl:50663,kl:36387,ll:14908,ml:37533,nl:105443,ol:61635,pl:62274,ql:133818,rl:65702,sl:65703,ul:65701,vl:76256,wl:37671,xl:49953,zl:36216,Al:28237,Bl:39553,Cl:29222,Dl:26107,El:38050,Fl:26108,Hl:120745,
Gl:26109,Il:26110,Jl:66881,Kl:28236,Ll:14586,Ml:57929,Nl:74723,Ol:44098,Pl:44099,Sl:23528,Tl:61699,Ql:134104,Rl:134103,Ul:59149,Vl:101951,Wl:97346,Xl:118051,Yl:95102,Zl:64882,am:119505,bm:63595,cm:63349,dm:95101,em:75240,fm:27039,gm:68823,hm:21537,im:83464,jm:75707,km:83113,lm:101952,mm:101953,om:79610,pm:125755,qm:24402,rm:24400,sm:32925,um:57173,tm:156421,vm:122502,wm:145268,xm:138480,ym:64423,zm:64424,Am:33986,Bm:100828,Cm:129089,Dm:21409,Hm:135155,Im:135156,Jm:135157,Km:135158,Lm:135159,Mm:135160,
Nm:135161,Om:135162,Pm:135163,Qm:135164,Rm:135165,Sm:135166,Em:11070,Fm:11074,Gm:17880,Tm:14001,Vm:30709,Wm:30707,Xm:30711,Ym:30710,Zm:30708,Um:26984,an:146143,bn:63648,cn:63649,dn:51879,en:111059,fn:5754,gn:20445,hn:151308,jn:151152,ln:130975,kn:130976,mn:110386,nn:113746,pn:66557,rn:17310,sn:28631,tn:21589,un:154946,vn:68012,wn:60480,xn:138664,yn:141121,zn:31571,An:141978,Bn:150105,Cn:150106,Dn:150107,En:150108,Fn:76980,Gn:41577,Hn:45469,Jn:38669,Kn:13768,Ln:13777,Mn:141842,Nn:62985,On:4724,Pn:59369,
Qn:43927,Rn:43928,Sn:12924,Tn:100355,Wn:56219,Xn:27669,Yn:10337,Vn:47896,Zn:122629,bo:139723,ao:139722,co:121258,eo:107598,fo:127991,ho:96639,jo:107536,ko:130169,lo:96661,mo:145188,no:96658,oo:116646,po:121122,qo:96660,ro:127738,so:127083,to:147842,uo:104443,vo:96659,wo:147595,xo:106442,yo:134840,zo:63667,Ao:63668,Bo:63669,Co:130686,Do:147036,Eo:78314,Fo:147799,Go:148649,Ho:55761,Io:127098,Jo:134841,Ko:96368,Lo:67374,Mo:48992,No:146176,Oo:49956,Po:31961,Qo:26388,Ro:23811,So:5E4,To:126250,Uo:96370,
Vo:47355,Wo:47356,Xo:37935,Yo:45521,Zo:21760,ap:83769,bp:49977,cp:49974,ep:93497,fp:93498,gp:34325,hp:140759,ip:115803,jp:123707,kp:100081,lp:35309,mp:68314,np:25602,qp:100339,rp:143516,sp:59018,tp:18248,up:50625,vp:9729,wp:37168,xp:37169,yp:21667,zp:16749,Ap:18635,Bp:39305,Cp:18046,Dp:53969,Ep:8213,Fp:93926,Gp:102852,Hp:110099,Ip:22678,Jp:69076,Kp:137575,Mp:139224,Np:100856,Op:154430,Pp:17736,Qp:3832,Rp:147111,Sp:55759,Tp:64031,Zp:93044,aq:93045,bq:34388,cq:17657,fq:17655,gq:39579,hq:39578,iq:77448,
jq:8196,kq:11357,lq:69877,mq:8197,nq:156512,oq:156509,pq:82039};function xs(){var a=vb(ys),b;return(new yf(function(c,d){a.onSuccess=function(e){gl(e)?c(new zs(e)):d(new As("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new As("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new As("Request timed out","net.timeout",e))};
b=ol("//googleads.g.doubleclick.net/pagead/id",a)})).gb(function(c){c instanceof Ff&&b.abort();
return Df(c)})}
function As(a,b,c){ab.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
t(As,ab);function zs(a){this.xhr=a}
;function Bs(){this.i=0;this.ja=null}
Bs.prototype.then=function(a,b,c){return 1===this.i&&a?(a=a.call(c,this.ja))&&"function"===typeof a.then?a:Cs(a):2===this.i&&b?(a=b.call(c,this.ja))&&"function"===typeof a.then?a:Ds(a):this};
Bs.prototype.getValue=function(){return this.ja};
Bs.prototype.$goog_Thenable=!0;function Ds(a){var b=new Bs;a=void 0===a?null:a;b.i=2;b.ja=void 0===a?null:a;return b}
function Cs(a){var b=new Bs;a=void 0===a?null:a;b.i=1;b.ja=void 0===a?null:a;return b}
;function Es(a,b){if(a)return a[b.name]}
;function Fs(a,b){var c=void 0===c?{}:c;a={method:void 0===b?"POST":b,mode:bl(a)?"same-origin":"cors",credentials:bl(a)?"same-origin":"include"};b={};for(var d=p(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);0<Object.keys(b).length&&(a.headers=b);return a}
;function Gs(){return sg()||km&&lm("applewebkit")&&!lm("version")&&(!lm("safari")||lm("gsa/"))||Qc&&lm("version/")?!0:L("EOM_VISITOR_DATA")?!1:!0}
;function Hs(a){a:{var b=a.raw_embedded_player_response;if(!b&&(a=a.embedded_player_response))try{b=JSON.parse(a)}catch(d){b="EMBEDDED_PLAYER_MODE_UNKNOWN";break a}if(b)b:{for(var c in Yh)if(Yh[c]==b.embeddedPlayerMode){b=Yh[c];break b}b="EMBEDDED_PLAYER_MODE_UNKNOWN"}else b="EMBEDDED_PLAYER_MODE_UNKNOWN"}return"EMBEDDED_PLAYER_MODE_PFL"===b}
;function Is(a){ab.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Js;this.isTimeout=a instanceof As&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof Ff}
t(Is,ab);Is.prototype.name="BiscottiError";function Js(){ab.call(this,"Biscotti ID is missing from server")}
t(Js,ab);Js.prototype.name="BiscottiMissingError";var ys={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Ks=null;function Ls(){if(M("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!Gs())return Error("User has not consented - not fetching biscotti id.");var a=L("PLAYER_VARS",{});if("1"==tb(a))return Error("Biscotti ID is not available in private embed mode");if(Hs(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Rk(){var a=Ls();if(void 0!==a)return Df(a);Ks||(Ks=xs().then(Ms).gb(function(b){return Ns(2,b)}));
return Ks}
function Ms(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new Js;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new Js;a=a.id;Sk(a);Ks=Cs(a);Os(18E5,2);return a}
function Ns(a,b){b=new Is(b);Sk("");Ks=Ds(b);0<a&&Os(12E4,a-1);throw b;}
function Os(a,b){hl(function(){xs().then(Ms,function(c){return Ns(b,c)}).gb(cb)},a)}
function Ps(){try{var a=B("yt.ads.biscotti.getId_");return a?a():Rk()}catch(b){return Df(b)}}
;function Qs(a){if("1"!=tb(L("PLAYER_VARS",{}))){a&&Qk();try{Ps().then(function(){},function(){}),hl(Qs,18E5)}catch(b){Ok(b)}}}
;function Rs(){this.ld=!0}
function Ss(a){var b={},c=ug([]);c&&(b.Authorization=c,c=a=null==a?void 0:a.sessionIndex,void 0===c&&(c=Number(L("SESSION_INDEX",0)),c=isNaN(c)?0:c),M("voice_search_auth_header_removal")||(b["X-Goog-AuthUser"]=c),"INNERTUBE_HOST_OVERRIDE"in Ek||(b["X-Origin"]=window.location.origin),void 0===a&&"DELEGATED_SESSION_ID"in Ek&&(b["X-Goog-PageId"]=L("DELEGATED_SESSION_ID")));return b}
;var Ts=Symbol("injectionDeps");function Us(a){this.name=a}
Us.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function Vs(){this.key=Ws}
function Xs(){this.providers=new Map;this.i=new Map}
Xs.prototype.resolve=function(a){return a instanceof Vs?Ys(this,a.key,[],!0):Ys(this,a,[])};
function Ys(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.i.has(b))return a.i.get(b);if(!a.providers.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.providers.get(b);c.push(b);if(d.nc)var e=d.nc;else if(d.sd)e=d[Ts]?Zs(a,d[Ts],c):[],e=d.sd.apply(d,ha(e));else if(d.mc){e=d.mc;var f=e[Ts]?Zs(a,e[Ts],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ha(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.Lq||a.i.set(b,e);
return e}
function Zs(a,b,c){return b?b.map(function(d){return d instanceof Vs?Ys(a,d.key,c,!0):Ys(a,d,c)}):[]}
;var $s;function at(){$s||($s=new Xs);return $s}
;var bt={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};var ct=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function dt(){var a=void 0===a?window.location.href:a;if(M("kevlar_disable_theme_param"))return null;mc(nc(5,a));try{var b=$k(a).theme;return ct.get(b)||null}catch(c){}return null}
;function et(){this.i={};if(this.j=zl()){var a=qg.get("CONSISTENCY",void 0);a&&ft(this,{encryptedTokenJarContents:a})}}
et.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=(null==(c=b.ga.context)?void 0:null==(d=c.request)?void 0:d.consistencyTokenJars)||[];var e;if(a=null==(e=a.responseContext)?void 0:e.consistencyTokenJar){e=p(b);for(c=e.next();!c.done;c=e.next())delete this.i[c.value.encryptedTokenJarContents];ft(this,a)}};
function ft(a,b){if(b.encryptedTokenJarContents&&(a.i[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.i[b.encryptedTokenJarContents]},1E3*c);
a.j&&yl("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var gt=window.location.hostname.split(".").slice(-2).join(".");function ht(){var a=L("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===L("INNERTUBE_CLIENT_NAME")&&(this.i=jt(this))&&(a=this.i.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.j=void 0)}
var kt;ht.getInstance=function(){kt=B("yt.clientLocationService.instance");kt||(kt=new ht,z("yt.clientLocationService.instance",kt));return kt};
ht.prototype.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.j?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(1E7*this.j.coords.latitude),a.client.locationInfo.longitudeE7=Math.floor(1E7*this.j.coords.longitude),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.j.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
ht.prototype.handleResponse=function(a){var b;a=null==(b=a.responseContext)?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.j=void 0,"TVHTML5"===L("INNERTUBE_CLIENT_NAME")?(this.i=jt(this))&&this.i.set("yt-location-playability-token",a,15552E3):yl("YT_CL",JSON.stringify({loctok:a}),15552E3,gt,!0))};
function jt(a){return void 0===a.i?new Xl("yt-client-location"):a.i}
ht.prototype.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;"MWEB"===L("INNERTUBE_CLIENT_NAME")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.j=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
ht.prototype.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null==a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};function lt(a,b){var c,d=null==(c=Es(a,ej))?void 0:c.signal;if(d&&b.La&&(c=b.La[d]))return c();var e;if((c=null==(e=Es(a,cj))?void 0:e.request)&&b.Bc&&(e=b.Bc[c]))return e();for(var f in a)if(b.Lb[f]&&(a=b.Lb[f]))return a()}
;function mt(a){return function(){return new a}}
;var nt={},ot=(nt.WEB_UNPLUGGED="^unplugged/",nt.WEB_UNPLUGGED_ONBOARDING="^unplugged/",nt.WEB_UNPLUGGED_OPS="^unplugged/",nt.WEB_UNPLUGGED_PUBLIC="^unplugged/",nt.WEB_CREATOR="^creator/",nt.WEB_KIDS="^kids/",nt.WEB_EXPERIMENTS="^experiments/",nt.WEB_MUSIC="^music/",nt.WEB_REMIX="^music/",nt.WEB_MUSIC_EMBEDDED_PLAYER="^music/",nt.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",nt);
function pt(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=ot[b];if(c){var d=new RegExp(c),e=p(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries(ot).forEach(function(g){var h=p(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=p(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function qt(){}
qt.prototype.o=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?bt:c;var d=a.clickTrackingParams,e=this.m,f=!1;f=void 0===f?!1:f;e=void 0===e?!1:e;var g=L("INNERTUBE_CONTEXT");if(g){g=wb(g);M("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;"MWEB"===h.clientName&&(h.clientFormFactor=L("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||
1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=void 0===k?!1:k;Bl.getInstance();var m="USER_INTERFACE_THEME_LIGHT";El(165)?m="USER_INTERFACE_THEME_DARK":El(174)?m="USER_INTERFACE_THEME_LIGHT":!M("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(m="USER_INTERFACE_THEME_DARK");k=k?m:dt()||m;h.userInterfaceTheme=k;if(!f){if(k=
Ll())h.connectionType=k;M("web_log_effective_connection_type")&&(k=Ml())&&(g.client.effectiveConnectionType=k)}var q;if(M("web_log_memory_total_kbytes")&&(null==(q=y.navigator)?0:q.deviceMemory)){var r;q=null==(r=y.navigator)?void 0:r.deviceMemory;g.client.memoryTotalKbytes=""+1E6*q}r=$k(y.location.href);!M("web_populate_internal_geo_killswitch")&&r.internalcountrycode&&(h.internalGeo=r.internalcountrycode);"MWEB"===h.clientName||"WEB"===h.clientName?(h.mainAppWebInfo={graftUrl:y.location.href},M("kevlar_woffle")&&
wl.i&&(r=wl.i,h.mainAppWebInfo.pwaInstallabilityStatus=!r.i&&r.j?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=xl(),h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):"TVHTML5"===h.clientName&&(!M("web_lr_app_quality_killswitch")&&(r=L("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:r})),r=L("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||
{},{certificationScope:r}));if(!M("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var w=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(lb){}w=void 0}w&&(h.timeZone=w)}(w=Jk())?h.experimentsToken=w:delete h.experimentsToken;w=Kk();et.i||(et.i=new et);h=et.i.i;r=[];q=0;for(var u in h)r[q++]=h[u];g.request=Object.assign({},g.request,{internalExperimentFlags:w,consistencyTokenJars:r});!M("web_prequest_context_killswitch")&&(u=L("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&
(g.request.externalPrequestContext=u);w=Bl.getInstance();u=El(58);w=w.get("gsml","");g.user=Object.assign({},g.user);u&&(g.user.enableSafetyMode=u);w&&(g.user.lockedSafetyMode=!0);M("warm_op_csn_cleanup")?e&&(f=qs())&&(g.clientScreenNonce=f):!f&&(f=qs())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=B("yt.mdx.remote.remoteClient_"))g.remoteClient=d;M("web_enable_client_location_service")&&ht.getInstance().setLocationOnInnerTubeContext(g);try{var A=cl(),E=A.bid;delete A.bid;
g.adSignalsInfo={params:[],bid:E};var F=p(Object.entries(A));for(var N=F.next();!N.done;N=F.next()){var O=p(N.value),R=O.next().value,U=O.next().value;A=R;E=U;d=void 0;null==(d=g.adSignalsInfo.params)||d.push({key:A,value:""+E})}}catch(lb){Yr(lb)}F=g}else Yr(Error("Error: No InnerTubeContext shell provided in ytconfig.")),F={};F={context:F};if(N=this.i(a)){this.j(F,N,b);var ca;b="/youtubei/v1/"+pt(this.l());(N=null==(ca=Es(a.commandMetadata,dj))?void 0:ca.apiUrl)&&(b=N);ca=b;(b=L("INNERTUBE_HOST_OVERRIDE"))&&
(ca=String(b)+String(pc(ca)));b={};b.key=L("INNERTUBE_API_KEY");M("json_condensed_response")&&(b.prettyPrint="false");ca=al(ca,b||{},!1);a=M("kevlar_response_command_processor_page")?Object.assign({},{command:a},void 0):Object.assign({},void 0);a={input:ca,va:Fs(ca),ga:F,config:a};a.config.Ra?a.config.Ra.identity=c:a.config.Ra={identity:c};return a}Yr(new Q("Error: Failed to create Request from Command.",a))};
ea.Object.defineProperties(qt.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!1}}});function rt(){}
t(rt,qt);rt.prototype.o=function(){return{input:"/getDatasyncIdsEndpoint",va:Fs("/getDatasyncIdsEndpoint","GET"),ga:{}}};
rt.prototype.l=function(){return[]};
rt.prototype.i=function(){};
rt.prototype.j=function(){};var st={},tt=(st.GET_DATASYNC_IDS=mt(rt),st);function ut(a){var b=Ja.apply(1,arguments);if(!vt(a)||b.some(function(d){return!vt(d)}))throw Error("Only objects may be merged.");
b=p(b);for(var c=b.next();!c.done;c=b.next())wt(a,c.value);return a}
function wt(a,b){for(var c in b)if(vt(b[c])){if(c in a&&!vt(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});wt(a[c],b[c])}else if(xt(b[c])){if(c in a&&!xt(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);zt(a[c],b[c])}else a[c]=b[c];return a}
function zt(a,b){b=p(b);for(var c=b.next();!c.done;c=b.next())c=c.value,vt(c)?a.push(wt({},c)):xt(c)?a.push(zt([],c)):a.push(c);return a}
function vt(a){return"object"===typeof a&&!Array.isArray(a)}
function xt(a){return"object"===typeof a&&Array.isArray(a)}
;function At(a,b){bo.call(this,1,arguments);this.timer=b}
t(At,bo);var Bt=new co("aft-recorded",At);var Ct=window;function Dt(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var S=Ct.performance||Ct.mozPerformance||Ct.msPerformance||Ct.webkitPerformance||new Dt;var Et=!1,Ft={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Wa(S.clearResourceTimings||S.webkitClearResourceTimings||S.mozClearResourceTimings||S.msClearResourceTimings||S.oClearResourceTimings||cb,S);function Gt(a){var b=Ht(a);if(b.aft)return b.aft;a=L((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=a.length,d=0;d<c;d++){var e=b[a[d]];if(e)return e}return NaN}
function It(){var a;if(M("csi_use_performance_navigation_timing")||M("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=null==S?void 0:null==(a=S.getEntriesByType)?void 0:null==(b=a.call(S,"navigation"))?void 0:null==(c=b[0])?void 0:null==(d=c.toJSON)?void 0:d.call(c);e?(e.requestStart=Jt(e.requestStart),e.responseEnd=Jt(e.responseEnd),e.redirectStart=Jt(e.redirectStart),e.redirectEnd=Jt(e.redirectEnd),e.domainLookupEnd=Jt(e.domainLookupEnd),e.connectStart=Jt(e.connectStart),e.connectEnd=
Jt(e.connectEnd),e.responseStart=Jt(e.responseStart),e.secureConnectionStart=Jt(e.secureConnectionStart),e.domainLookupStart=Jt(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=S.timing}else a=S.timing;return a}
function Kt(){return(M("csi_use_time_origin")||M("csi_use_time_origin_tvhtml5"))&&S.timeOrigin?Math.floor(S.timeOrigin):S.timing.navigationStart}
function Jt(a){return Math.round(Kt()+a)}
function Lt(a){var b;(b=B("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},z("ytcsi."+(a||"")+"data_",b));return b}
function Mt(a){a=Lt(a);a.info||(a.info={});return a.info}
function Ht(a){a=Lt(a);a.tick||(a.tick={});return a.tick}
function Nt(a){a=Lt(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function Ot(a){a=Nt(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function Pt(a){a=Nt(a);a.jspbInfos||(a.jspbInfos=[]);return a.jspbInfos}
function Qt(a){var b=Lt(a).nonce;b||(b=fs(),Lt(a).nonce=b);return b}
function Rt(a){var b=Ht(a||""),c=Gt(a);c&&!Et&&(io(Bt,new At(Math.round(c-b._start),a)),Et=!0)}
function St(a,b){for(var c=p(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!St(a[d],b[d]))return!1;return!0}
function Tt(){for(var a=Pt(),b=0;b<a.length&&"cold"!==Sd(a[b],3,"");b++);}
;function Ut(){if(S.getEntriesByType){var a=S.getEntriesByType("paint");if(a=kb(a,function(b){return"first-paint"===b.name}))return Jt(a.startTime)}a=S.timing;
return a.Qc?Math.max(0,a.Qc):0}
;function Vt(){var a=B("ytcsi.debug");a||(a=[],z("ytcsi.debug",a),z("ytcsi.reference",{}));return a}
function Wt(a){a=a||"";var b=B("ytcsi.reference");b||(Vt(),b=B("ytcsi.reference"));if(b[a])return b[a];var c=Vt(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var T={},Xt=(T.auto_search="LATENCY_ACTION_AUTO_SEARCH",T.ad_to_ad="LATENCY_ACTION_AD_TO_AD",T.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",T["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",T.app_startup="LATENCY_ACTION_APP_STARTUP",T["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",T["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",T["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",T["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",T.browse="LATENCY_ACTION_BROWSE",
T.cast_splash="LATENCY_ACTION_CAST_SPLASH",T.channels="LATENCY_ACTION_CHANNELS",T.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",T["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",T["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",T["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",T["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",T["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",T["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",
T["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",T["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",T["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",T["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",T["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",T["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",T["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",T.chips="LATENCY_ACTION_CHIPS",
T["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",T["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",T["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",T.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",T.embed="LATENCY_ACTION_EMBED",T.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",T.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",T.explore="LATENCY_ACTION_EXPLORE",T.home=
"LATENCY_ACTION_HOME",T.library="LATENCY_ACTION_LIBRARY",T.live="LATENCY_ACTION_LIVE",T.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",T.onboarding="LATENCY_ACTION_ONBOARDING",T.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",T.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",T.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",T.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",T["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",T["post.edit"]=
"LATENCY_ACTION_CREATOR_POST_EDIT",T.prebuffer="LATENCY_ACTION_PREBUFFER",T.prefetch="LATENCY_ACTION_PREFETCH",T.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",T.profile_switcher="LATENCY_ACTION_LOGIN",T.reel_watch="LATENCY_ACTION_REEL_WATCH",T.results="LATENCY_ACTION_RESULTS",T["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",T.search_ui="LATENCY_ACTION_SEARCH_UI",T.search_suggest="LATENCY_ACTION_SUGGEST",T.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",T.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",
T.seek="LATENCY_ACTION_PLAYER_SEEK",T.settings="LATENCY_ACTION_SETTINGS",T.store="LATENCY_ACTION_STORE",T.tenx="LATENCY_ACTION_TENX",T.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",T.watch="LATENCY_ACTION_WATCH",T.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",T["watch,watch7"]="LATENCY_ACTION_WATCH",T["watch,watch7_html5"]="LATENCY_ACTION_WATCH",T["watch,watch7ad"]="LATENCY_ACTION_WATCH",T["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",T.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",T.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",
T["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",T["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",T["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",T["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",T["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",T["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",T["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",T["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",
T["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",T.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",T.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",T.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",T),V={},Yt=(V.ad_allowed="adTypesAllowed",V.yt_abt="adBreakType",V.ad_cpn="adClientPlaybackNonce",V.ad_docid="adVideoId",V.yt_ad_an="adNetworks",V.ad_at="adType",V.aida="appInstallDataAgeMs",V.browse_id="browseId",V.p="httpProtocol",V.t="transportProtocol",
V.cs="commandSource",V.cpn="clientPlaybackNonce",V.ccs="creatorInfo.creatorCanaryState",V.ctop="creatorInfo.topEntityType",V.csn="clientScreenNonce",V.docid="videoId",V.GetHome_rid="requestIds",V.GetSearch_rid="requestIds",V.GetPlayer_rid="requestIds",V.GetWatchNext_rid="requestIds",V.GetBrowse_rid="requestIds",V.GetLibrary_rid="requestIds",V.is_continuation="isContinuation",V.is_nav="isNavigation",V.b_p="kabukiInfo.browseParams",V.is_prefetch="kabukiInfo.isPrefetch",V.is_secondary_nav="kabukiInfo.isSecondaryNav",
V.nav_type="kabukiInfo.navigationType",V.prev_browse_id="kabukiInfo.prevBrowseId",V.query_source="kabukiInfo.querySource",V.voz_type="kabukiInfo.vozType",V.yt_lt="loadType",V.mver="creatorInfo.measurementVersion",V.yt_ad="isMonetized",V.nr="webInfo.navigationReason",V.nrsu="navigationRequestedSameUrl",V.pnt="performanceNavigationTiming",V.prt="playbackRequiresTap",V.plt="playerInfo.playbackType",V.pis="playerInfo.playerInitializedState",V.paused="playerInfo.isPausedOnLoad",V.yt_pt="playerType",V.fmt=
"playerInfo.itag",V.yt_pl="watchInfo.isPlaylist",V.yt_pre="playerInfo.preloadType",V.yt_ad_pr="prerollAllowed",V.pa="previousAction",V.yt_red="isRedSubscriber",V.rce="mwebInfo.responseContentEncoding",V.rc="resourceInfo.resourceCache",V.scrh="screenHeight",V.scrw="screenWidth",V.st="serverTimeMs",V.ssdm="shellStartupDurationMs",V.br_trs="tvInfo.bedrockTriggerState",V.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",V.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",V.label="tvInfo.label",
V.is_mdx="tvInfo.isMdx",V.preloaded="tvInfo.isPreloaded",V.aac_type="tvInfo.authAccessCredentialType",V.upg_player_vis="playerInfo.visibilityState",V.query="unpluggedInfo.query",V.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",V.yt_vst="videoStreamType",V.vph="viewportHeight",V.vpw="viewportWidth",V.yt_vis="isVisible",V.rcl="mwebInfo.responseContentLength",V.GetSettings_rid="requestIds",V.GetTrending_rid="requestIds",V.GetMusicSearchSuggestions_rid="requestIds",V.REQUEST_ID="requestIds",V),
Zt="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),$t={},au=($t.ccs="CANARY_STATE_",$t.mver="MEASUREMENT_VERSION_",$t.pis="PLAYER_INITIALIZED_STATE_",$t.yt_pt="LATENCY_PLAYER_",$t.pa="LATENCY_ACTION_",$t.ctop="TOP_ENTITY_TYPE_",
$t.yt_vst="VIDEO_STREAM_TYPE_",$t),bu="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");function cu(a){return Xt[a]||"LATENCY_ACTION_UNKNOWN"}
function du(a,b,c){c=Nt(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in Yt){c=Yt[a];0<=eb(Zt,c)&&(b=!!b);a in au&&"string"===typeof b&&(b=au[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return ut({},d)}0<=eb(bu,a)||Zr(new Q("Unknown label logged with GEL CSI",a))}
;var W={LATENCY_ACTION_KIDS_PROFILE_SWITCHER:90,LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER:100,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC:46,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR:37,LATENCY_ACTION_SPINNER_DISPLAYED:14,LATENCY_ACTION_PLAYABILITY_CHECK:10,LATENCY_ACTION_PROCESS:9,LATENCY_ACTION_APP_STARTUP:5,LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING:179,LATENCY_ACTION_COMMERCE_TRANSACTION:184,LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC:173,LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC:172,
LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC:171,LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC:170,LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC:169,LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC:168,LATENCY_ACTION_GET_OFFERS_RPC:167,LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC:166,LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC:165,LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC:164,LATENCY_ACTION_GET_OFFER_DETAILS_RPC:163,LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC:162,LATENCY_ACTION_GET_TIP_MODULE_RPC:161,LATENCY_ACTION_HANDLE_TRANSACTION_RPC:160,
LATENCY_ACTION_COMPLETE_TRANSACTION_RPC:159,LATENCY_ACTION_GET_CART_RPC:158,LATENCY_ACTION_THUMBNAIL_FETCH:156,LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK:154,LATENCY_ACTION_SHARE_VIDEO:153,LATENCY_ACTION_AD_TO_VIDEO_INT:152,LATENCY_ACTION_ABANDONED_BROWSE:151,LATENCY_ACTION_PLAYER_ROTATION:150,LATENCY_ACTION_GENERIC_WEB_VIEW:183,LATENCY_ACTION_SHOPPING_IN_APP:124,LATENCY_ACTION_PLAYER_ATTESTATION:121,LATENCY_ACTION_PLAYER_SEEK:119,LATENCY_ACTION_SUPER_STICKER_BUY_FLOW:114,LATENCY_ACTION_DOWNLOADS_DATA_ACCESS:180,
LATENCY_ACTION_BLOCKS_PERFORMANCE:148,LATENCY_ACTION_ASSISTANT_QUERY:138,LATENCY_ACTION_ASSISTANT_SETTINGS:137,LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF:129,LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF:128,LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE:127,LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION:123,LATENCY_ACTION_NETWORKLESS_PERFORMANCE:122,LATENCY_ACTION_DOWNLOADS_EXPANSION:133,LATENCY_ACTION_ENTITY_TRANSFORM:131,LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER:96,LATENCY_ACTION_EMBEDS_SET_VIDEO:95,
LATENCY_ACTION_SETTINGS:93,LATENCY_ACTION_ABANDONED_STARTUP:81,LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY:80,LATENCY_ACTION_MEDIA_BROWSER_SEARCH:79,LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE:78,LATENCY_ACTION_WHO_IS_WATCHING:77,LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH:76,LATENCY_ACTION_LITE_SWITCH_ACCOUNT:73,LATENCY_ACTION_ELEMENTS_PERFORMANCE:70,LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION:69,LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION:65,LATENCY_ACTION_OFFLINE_STORE_START:61,LATENCY_ACTION_REEL_EDITOR:58,
LATENCY_ACTION_CHANNEL_SUBSCRIBE:56,LATENCY_ACTION_CHANNEL_PREVIEW:55,LATENCY_ACTION_PREFETCH:52,LATENCY_ACTION_ABANDONED_WATCH:45,LATENCY_ACTION_LOAD_COMMENT_REPLIES:26,LATENCY_ACTION_LOAD_COMMENTS:25,LATENCY_ACTION_EDIT_COMMENT:24,LATENCY_ACTION_NEW_COMMENT:23,LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING:19,LATENCY_ACTION_EMBED:18,LATENCY_ACTION_MDX_LAUNCH:15,LATENCY_ACTION_RESOLVE_URL:13,LATENCY_ACTION_CAST_SPLASH:149,LATENCY_ACTION_MDX_STREAM_TRANSFER:178,LATENCY_ACTION_MDX_CAST:120,LATENCY_ACTION_MDX_COMMAND:12,
LATENCY_ACTION_REEL_SELECT_SEGMENT:136,LATENCY_ACTION_ACCELERATED_EFFECTS:145,LATENCY_ACTION_EDIT_AUDIO_GEN:182,LATENCY_ACTION_UPLOAD_AUDIO_MIXER:147,LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING:157,LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING:146,LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK:130,LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD:125,LATENCY_ACTION_SHORTS_VIDEO_INGESTION:155,LATENCY_ACTION_SHORTS_GALLERY:107,LATENCY_ACTION_SHORTS_TRIM:105,LATENCY_ACTION_SHORTS_EDIT:104,LATENCY_ACTION_SHORTS_CAMERA:103,
LATENCY_ACTION_PARENT_TOOLS_DASHBOARD:102,LATENCY_ACTION_PARENT_TOOLS_COLLECTION:101,LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS:116,LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS:115,LATENCY_ACTION_MUSIC_ALBUM_DETAIL:72,LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL:71,LATENCY_ACTION_STORE:175,LATENCY_ACTION_CHIPS:68,LATENCY_ACTION_SEARCH_ZERO_STATE:67,LATENCY_ACTION_LIVE_PAGINATION:117,LATENCY_ACTION_LIVE:20,LATENCY_ACTION_PREBUFFER:40,LATENCY_ACTION_TENX:39,LATENCY_ACTION_KIDS_PROFILE_SETTINGS:94,LATENCY_ACTION_KIDS_WATCH_IT_AGAIN:92,
LATENCY_ACTION_KIDS_SECRET_CODE:91,LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS:89,LATENCY_ACTION_KIDS_ONBOARDING:88,LATENCY_ACTION_KIDS_VOICE_SEARCH:82,LATENCY_ACTION_KIDS_CURATED_COLLECTION:62,LATENCY_ACTION_KIDS_LIBRARY:53,LATENCY_ACTION_CREATOR_PROMOTION_LIST:186,LATENCY_ACTION_CREATOR_PROMOTION_EDIT:185,LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS:38,LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION:74,LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING:141,LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS:142,LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC:51,
LATENCY_ACTION_CREATOR_VIDEO_EDITOR:50,LATENCY_ACTION_CREATOR_VIDEO_EDIT:36,LATENCY_ACTION_CREATOR_VIDEO_COMMENTS:34,LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS:33,LATENCY_ACTION_CREATOR_SONG_ANALYTICS:176,LATENCY_ACTION_CREATOR_POST_LIST:112,LATENCY_ACTION_CREATOR_POST_EDIT:110,LATENCY_ACTION_CREATOR_POST_COMMENTS:111,LATENCY_ACTION_CREATOR_LIVE_STREAMING:108,LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT:174,LATENCY_ACTION_CREATOR_DIALOG_UPLOADS:86,LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES:87,LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS:32,
LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS:48,LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS:139,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT:177,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC:99,LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION:43,LATENCY_ACTION_CREATOR_CHANNEL_EDITING:113,LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD:49,LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT:44,LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS:66,LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS:31,LATENCY_ACTION_CREATOR_ARTIST_PROFILE:85,LATENCY_ACTION_CREATOR_ARTIST_CONCERTS:84,
LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS:83,LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE:140,LATENCY_ACTION_EXPERIMENTAL_WATCH_UI:181,LATENCY_ACTION_STORYBOARD_THUMBNAILS:118,LATENCY_ACTION_SEARCH_THUMBNAILS:59,LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD:54,LATENCY_ACTION_VOICE_ASSISTANT:47,LATENCY_ACTION_SEARCH_UI:35,LATENCY_ACTION_SUGGEST:30,LATENCY_ACTION_AUTO_SEARCH:126,LATENCY_ACTION_DOWNLOADS:98,LATENCY_ACTION_EXPLORE:75,LATENCY_ACTION_VIDEO_LIST:63,LATENCY_ACTION_HOME_RESUME:60,LATENCY_ACTION_SUBSCRIPTIONS_LIST:57,
LATENCY_ACTION_THUMBNAIL_LOAD:42,LATENCY_ACTION_FIRST_THUMBNAIL_LOAD:29,LATENCY_ACTION_SUBSCRIPTIONS_FEED:109,LATENCY_ACTION_SUBSCRIPTIONS:28,LATENCY_ACTION_TRENDING:27,LATENCY_ACTION_LIBRARY:21,LATENCY_ACTION_VIDEO_THUMBNAIL:8,LATENCY_ACTION_SHOW_MORE:7,LATENCY_ACTION_VIDEO_PREVIEW:6,LATENCY_ACTION_PREBUFFER_VIDEO:144,LATENCY_ACTION_PREFETCH_VIDEO:143,LATENCY_ACTION_DIRECT_PLAYBACK:132,LATENCY_ACTION_REEL_WATCH:41,LATENCY_ACTION_AD_TO_AD:22,LATENCY_ACTION_VIDEO_TO_AD:17,LATENCY_ACTION_AD_TO_VIDEO:16,
LATENCY_ACTION_ONBOARDING:135,LATENCY_ACTION_LOGIN:97,LATENCY_ACTION_BROWSE:11,LATENCY_ACTION_CHANNELS:4,LATENCY_ACTION_WATCH:3,LATENCY_ACTION_RESULTS:2,LATENCY_ACTION_HOME:1,LATENCY_ACTION_STARTUP:106,LATENCY_ACTION_UNKNOWN:0};W[W.LATENCY_ACTION_KIDS_PROFILE_SWITCHER]="LATENCY_ACTION_KIDS_PROFILE_SWITCHER";W[W.LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER]="LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER";W[W.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC";
W[W.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR";W[W.LATENCY_ACTION_SPINNER_DISPLAYED]="LATENCY_ACTION_SPINNER_DISPLAYED";W[W.LATENCY_ACTION_PLAYABILITY_CHECK]="LATENCY_ACTION_PLAYABILITY_CHECK";W[W.LATENCY_ACTION_PROCESS]="LATENCY_ACTION_PROCESS";W[W.LATENCY_ACTION_APP_STARTUP]="LATENCY_ACTION_APP_STARTUP";W[W.LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING";W[W.LATENCY_ACTION_COMMERCE_TRANSACTION]="LATENCY_ACTION_COMMERCE_TRANSACTION";
W[W.LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC]="LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC";W[W.LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC]="LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC";W[W.LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC]="LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC";W[W.LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC]="LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC";W[W.LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC]="LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC";
W[W.LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC]="LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC";W[W.LATENCY_ACTION_GET_OFFERS_RPC]="LATENCY_ACTION_GET_OFFERS_RPC";W[W.LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC";W[W.LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC";W[W.LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC]="LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC";W[W.LATENCY_ACTION_GET_OFFER_DETAILS_RPC]="LATENCY_ACTION_GET_OFFER_DETAILS_RPC";
W[W.LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC]="LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC";W[W.LATENCY_ACTION_GET_TIP_MODULE_RPC]="LATENCY_ACTION_GET_TIP_MODULE_RPC";W[W.LATENCY_ACTION_HANDLE_TRANSACTION_RPC]="LATENCY_ACTION_HANDLE_TRANSACTION_RPC";W[W.LATENCY_ACTION_COMPLETE_TRANSACTION_RPC]="LATENCY_ACTION_COMPLETE_TRANSACTION_RPC";W[W.LATENCY_ACTION_GET_CART_RPC]="LATENCY_ACTION_GET_CART_RPC";W[W.LATENCY_ACTION_THUMBNAIL_FETCH]="LATENCY_ACTION_THUMBNAIL_FETCH";
W[W.LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK]="LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK";W[W.LATENCY_ACTION_SHARE_VIDEO]="LATENCY_ACTION_SHARE_VIDEO";W[W.LATENCY_ACTION_AD_TO_VIDEO_INT]="LATENCY_ACTION_AD_TO_VIDEO_INT";W[W.LATENCY_ACTION_ABANDONED_BROWSE]="LATENCY_ACTION_ABANDONED_BROWSE";W[W.LATENCY_ACTION_PLAYER_ROTATION]="LATENCY_ACTION_PLAYER_ROTATION";W[W.LATENCY_ACTION_GENERIC_WEB_VIEW]="LATENCY_ACTION_GENERIC_WEB_VIEW";W[W.LATENCY_ACTION_SHOPPING_IN_APP]="LATENCY_ACTION_SHOPPING_IN_APP";
W[W.LATENCY_ACTION_PLAYER_ATTESTATION]="LATENCY_ACTION_PLAYER_ATTESTATION";W[W.LATENCY_ACTION_PLAYER_SEEK]="LATENCY_ACTION_PLAYER_SEEK";W[W.LATENCY_ACTION_SUPER_STICKER_BUY_FLOW]="LATENCY_ACTION_SUPER_STICKER_BUY_FLOW";W[W.LATENCY_ACTION_DOWNLOADS_DATA_ACCESS]="LATENCY_ACTION_DOWNLOADS_DATA_ACCESS";W[W.LATENCY_ACTION_BLOCKS_PERFORMANCE]="LATENCY_ACTION_BLOCKS_PERFORMANCE";W[W.LATENCY_ACTION_ASSISTANT_QUERY]="LATENCY_ACTION_ASSISTANT_QUERY";W[W.LATENCY_ACTION_ASSISTANT_SETTINGS]="LATENCY_ACTION_ASSISTANT_SETTINGS";
W[W.LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF";W[W.LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF";W[W.LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE]="LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE";W[W.LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION]="LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION";W[W.LATENCY_ACTION_NETWORKLESS_PERFORMANCE]="LATENCY_ACTION_NETWORKLESS_PERFORMANCE";
W[W.LATENCY_ACTION_DOWNLOADS_EXPANSION]="LATENCY_ACTION_DOWNLOADS_EXPANSION";W[W.LATENCY_ACTION_ENTITY_TRANSFORM]="LATENCY_ACTION_ENTITY_TRANSFORM";W[W.LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER]="LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER";W[W.LATENCY_ACTION_EMBEDS_SET_VIDEO]="LATENCY_ACTION_EMBEDS_SET_VIDEO";W[W.LATENCY_ACTION_SETTINGS]="LATENCY_ACTION_SETTINGS";W[W.LATENCY_ACTION_ABANDONED_STARTUP]="LATENCY_ACTION_ABANDONED_STARTUP";W[W.LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY]="LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY";
W[W.LATENCY_ACTION_MEDIA_BROWSER_SEARCH]="LATENCY_ACTION_MEDIA_BROWSER_SEARCH";W[W.LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE]="LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE";W[W.LATENCY_ACTION_WHO_IS_WATCHING]="LATENCY_ACTION_WHO_IS_WATCHING";W[W.LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH]="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH";W[W.LATENCY_ACTION_LITE_SWITCH_ACCOUNT]="LATENCY_ACTION_LITE_SWITCH_ACCOUNT";W[W.LATENCY_ACTION_ELEMENTS_PERFORMANCE]="LATENCY_ACTION_ELEMENTS_PERFORMANCE";
W[W.LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION]="LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION";W[W.LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION]="LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION";W[W.LATENCY_ACTION_OFFLINE_STORE_START]="LATENCY_ACTION_OFFLINE_STORE_START";W[W.LATENCY_ACTION_REEL_EDITOR]="LATENCY_ACTION_REEL_EDITOR";W[W.LATENCY_ACTION_CHANNEL_SUBSCRIBE]="LATENCY_ACTION_CHANNEL_SUBSCRIBE";W[W.LATENCY_ACTION_CHANNEL_PREVIEW]="LATENCY_ACTION_CHANNEL_PREVIEW";W[W.LATENCY_ACTION_PREFETCH]="LATENCY_ACTION_PREFETCH";
W[W.LATENCY_ACTION_ABANDONED_WATCH]="LATENCY_ACTION_ABANDONED_WATCH";W[W.LATENCY_ACTION_LOAD_COMMENT_REPLIES]="LATENCY_ACTION_LOAD_COMMENT_REPLIES";W[W.LATENCY_ACTION_LOAD_COMMENTS]="LATENCY_ACTION_LOAD_COMMENTS";W[W.LATENCY_ACTION_EDIT_COMMENT]="LATENCY_ACTION_EDIT_COMMENT";W[W.LATENCY_ACTION_NEW_COMMENT]="LATENCY_ACTION_NEW_COMMENT";W[W.LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING]="LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING";W[W.LATENCY_ACTION_EMBED]="LATENCY_ACTION_EMBED";
W[W.LATENCY_ACTION_MDX_LAUNCH]="LATENCY_ACTION_MDX_LAUNCH";W[W.LATENCY_ACTION_RESOLVE_URL]="LATENCY_ACTION_RESOLVE_URL";W[W.LATENCY_ACTION_CAST_SPLASH]="LATENCY_ACTION_CAST_SPLASH";W[W.LATENCY_ACTION_MDX_STREAM_TRANSFER]="LATENCY_ACTION_MDX_STREAM_TRANSFER";W[W.LATENCY_ACTION_MDX_CAST]="LATENCY_ACTION_MDX_CAST";W[W.LATENCY_ACTION_MDX_COMMAND]="LATENCY_ACTION_MDX_COMMAND";W[W.LATENCY_ACTION_REEL_SELECT_SEGMENT]="LATENCY_ACTION_REEL_SELECT_SEGMENT";W[W.LATENCY_ACTION_ACCELERATED_EFFECTS]="LATENCY_ACTION_ACCELERATED_EFFECTS";
W[W.LATENCY_ACTION_EDIT_AUDIO_GEN]="LATENCY_ACTION_EDIT_AUDIO_GEN";W[W.LATENCY_ACTION_UPLOAD_AUDIO_MIXER]="LATENCY_ACTION_UPLOAD_AUDIO_MIXER";W[W.LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING]="LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING";W[W.LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING]="LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING";W[W.LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK]="LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK";W[W.LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD]="LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD";
W[W.LATENCY_ACTION_SHORTS_VIDEO_INGESTION]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION";W[W.LATENCY_ACTION_SHORTS_GALLERY]="LATENCY_ACTION_SHORTS_GALLERY";W[W.LATENCY_ACTION_SHORTS_TRIM]="LATENCY_ACTION_SHORTS_TRIM";W[W.LATENCY_ACTION_SHORTS_EDIT]="LATENCY_ACTION_SHORTS_EDIT";W[W.LATENCY_ACTION_SHORTS_CAMERA]="LATENCY_ACTION_SHORTS_CAMERA";W[W.LATENCY_ACTION_PARENT_TOOLS_DASHBOARD]="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD";W[W.LATENCY_ACTION_PARENT_TOOLS_COLLECTION]="LATENCY_ACTION_PARENT_TOOLS_COLLECTION";
W[W.LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS";W[W.LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS";W[W.LATENCY_ACTION_MUSIC_ALBUM_DETAIL]="LATENCY_ACTION_MUSIC_ALBUM_DETAIL";W[W.LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL]="LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL";W[W.LATENCY_ACTION_STORE]="LATENCY_ACTION_STORE";W[W.LATENCY_ACTION_CHIPS]="LATENCY_ACTION_CHIPS";W[W.LATENCY_ACTION_SEARCH_ZERO_STATE]="LATENCY_ACTION_SEARCH_ZERO_STATE";
W[W.LATENCY_ACTION_LIVE_PAGINATION]="LATENCY_ACTION_LIVE_PAGINATION";W[W.LATENCY_ACTION_LIVE]="LATENCY_ACTION_LIVE";W[W.LATENCY_ACTION_PREBUFFER]="LATENCY_ACTION_PREBUFFER";W[W.LATENCY_ACTION_TENX]="LATENCY_ACTION_TENX";W[W.LATENCY_ACTION_KIDS_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PROFILE_SETTINGS";W[W.LATENCY_ACTION_KIDS_WATCH_IT_AGAIN]="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN";W[W.LATENCY_ACTION_KIDS_SECRET_CODE]="LATENCY_ACTION_KIDS_SECRET_CODE";W[W.LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS";
W[W.LATENCY_ACTION_KIDS_ONBOARDING]="LATENCY_ACTION_KIDS_ONBOARDING";W[W.LATENCY_ACTION_KIDS_VOICE_SEARCH]="LATENCY_ACTION_KIDS_VOICE_SEARCH";W[W.LATENCY_ACTION_KIDS_CURATED_COLLECTION]="LATENCY_ACTION_KIDS_CURATED_COLLECTION";W[W.LATENCY_ACTION_KIDS_LIBRARY]="LATENCY_ACTION_KIDS_LIBRARY";W[W.LATENCY_ACTION_CREATOR_PROMOTION_LIST]="LATENCY_ACTION_CREATOR_PROMOTION_LIST";W[W.LATENCY_ACTION_CREATOR_PROMOTION_EDIT]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT";
W[W.LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS";W[W.LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION";W[W.LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING";W[W.LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC";
W[W.LATENCY_ACTION_CREATOR_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDIT]="LATENCY_ACTION_CREATOR_VIDEO_EDIT";W[W.LATENCY_ACTION_CREATOR_VIDEO_COMMENTS]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS";W[W.LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_SONG_ANALYTICS]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_POST_LIST]="LATENCY_ACTION_CREATOR_POST_LIST";
W[W.LATENCY_ACTION_CREATOR_POST_EDIT]="LATENCY_ACTION_CREATOR_POST_EDIT";W[W.LATENCY_ACTION_CREATOR_POST_COMMENTS]="LATENCY_ACTION_CREATOR_POST_COMMENTS";W[W.LATENCY_ACTION_CREATOR_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_LIVE_STREAMING";W[W.LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT";W[W.LATENCY_ACTION_CREATOR_DIALOG_UPLOADS]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS";W[W.LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES";
W[W.LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION";
W[W.LATENCY_ACTION_CREATOR_CHANNEL_EDITING]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING";W[W.LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD]="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD";W[W.LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT";W[W.LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_ARTIST_PROFILE]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE";
W[W.LATENCY_ACTION_CREATOR_ARTIST_CONCERTS]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS";W[W.LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE";W[W.LATENCY_ACTION_EXPERIMENTAL_WATCH_UI]="LATENCY_ACTION_EXPERIMENTAL_WATCH_UI";W[W.LATENCY_ACTION_STORYBOARD_THUMBNAILS]="LATENCY_ACTION_STORYBOARD_THUMBNAILS";W[W.LATENCY_ACTION_SEARCH_THUMBNAILS]="LATENCY_ACTION_SEARCH_THUMBNAILS";
W[W.LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD]="LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD";W[W.LATENCY_ACTION_VOICE_ASSISTANT]="LATENCY_ACTION_VOICE_ASSISTANT";W[W.LATENCY_ACTION_SEARCH_UI]="LATENCY_ACTION_SEARCH_UI";W[W.LATENCY_ACTION_SUGGEST]="LATENCY_ACTION_SUGGEST";W[W.LATENCY_ACTION_AUTO_SEARCH]="LATENCY_ACTION_AUTO_SEARCH";W[W.LATENCY_ACTION_DOWNLOADS]="LATENCY_ACTION_DOWNLOADS";W[W.LATENCY_ACTION_EXPLORE]="LATENCY_ACTION_EXPLORE";W[W.LATENCY_ACTION_VIDEO_LIST]="LATENCY_ACTION_VIDEO_LIST";
W[W.LATENCY_ACTION_HOME_RESUME]="LATENCY_ACTION_HOME_RESUME";W[W.LATENCY_ACTION_SUBSCRIPTIONS_LIST]="LATENCY_ACTION_SUBSCRIPTIONS_LIST";W[W.LATENCY_ACTION_THUMBNAIL_LOAD]="LATENCY_ACTION_THUMBNAIL_LOAD";W[W.LATENCY_ACTION_FIRST_THUMBNAIL_LOAD]="LATENCY_ACTION_FIRST_THUMBNAIL_LOAD";W[W.LATENCY_ACTION_SUBSCRIPTIONS_FEED]="LATENCY_ACTION_SUBSCRIPTIONS_FEED";W[W.LATENCY_ACTION_SUBSCRIPTIONS]="LATENCY_ACTION_SUBSCRIPTIONS";W[W.LATENCY_ACTION_TRENDING]="LATENCY_ACTION_TRENDING";
W[W.LATENCY_ACTION_LIBRARY]="LATENCY_ACTION_LIBRARY";W[W.LATENCY_ACTION_VIDEO_THUMBNAIL]="LATENCY_ACTION_VIDEO_THUMBNAIL";W[W.LATENCY_ACTION_SHOW_MORE]="LATENCY_ACTION_SHOW_MORE";W[W.LATENCY_ACTION_VIDEO_PREVIEW]="LATENCY_ACTION_VIDEO_PREVIEW";W[W.LATENCY_ACTION_PREBUFFER_VIDEO]="LATENCY_ACTION_PREBUFFER_VIDEO";W[W.LATENCY_ACTION_PREFETCH_VIDEO]="LATENCY_ACTION_PREFETCH_VIDEO";W[W.LATENCY_ACTION_DIRECT_PLAYBACK]="LATENCY_ACTION_DIRECT_PLAYBACK";W[W.LATENCY_ACTION_REEL_WATCH]="LATENCY_ACTION_REEL_WATCH";
W[W.LATENCY_ACTION_AD_TO_AD]="LATENCY_ACTION_AD_TO_AD";W[W.LATENCY_ACTION_VIDEO_TO_AD]="LATENCY_ACTION_VIDEO_TO_AD";W[W.LATENCY_ACTION_AD_TO_VIDEO]="LATENCY_ACTION_AD_TO_VIDEO";W[W.LATENCY_ACTION_ONBOARDING]="LATENCY_ACTION_ONBOARDING";W[W.LATENCY_ACTION_LOGIN]="LATENCY_ACTION_LOGIN";W[W.LATENCY_ACTION_BROWSE]="LATENCY_ACTION_BROWSE";W[W.LATENCY_ACTION_CHANNELS]="LATENCY_ACTION_CHANNELS";W[W.LATENCY_ACTION_WATCH]="LATENCY_ACTION_WATCH";W[W.LATENCY_ACTION_RESULTS]="LATENCY_ACTION_RESULTS";
W[W.LATENCY_ACTION_HOME]="LATENCY_ACTION_HOME";W[W.LATENCY_ACTION_STARTUP]="LATENCY_ACTION_STARTUP";W[W.LATENCY_ACTION_UNKNOWN]="LATENCY_ACTION_UNKNOWN";var eu={LATENCY_NETWORK_MOBILE:2,LATENCY_NETWORK_WIFI:1,LATENCY_NETWORK_UNKNOWN:0};eu[eu.LATENCY_NETWORK_MOBILE]="LATENCY_NETWORK_MOBILE";eu[eu.LATENCY_NETWORK_WIFI]="LATENCY_NETWORK_WIFI";eu[eu.LATENCY_NETWORK_UNKNOWN]="LATENCY_NETWORK_UNKNOWN";
var X={CONN_INVALID:31,CONN_CELLULAR_5G_NSA:12,CONN_CELLULAR_5G_SA:11,CONN_WIFI_METERED:10,CONN_CELLULAR_5G:9,CONN_DISCO:8,CONN_CELLULAR_UNKNOWN:7,CONN_CELLULAR_4G:6,CONN_CELLULAR_3G:5,CONN_CELLULAR_2G:4,CONN_WIFI:3,CONN_NONE:2,CONN_UNKNOWN:1,CONN_DEFAULT:0};X[X.CONN_INVALID]="CONN_INVALID";X[X.CONN_CELLULAR_5G_NSA]="CONN_CELLULAR_5G_NSA";X[X.CONN_CELLULAR_5G_SA]="CONN_CELLULAR_5G_SA";X[X.CONN_WIFI_METERED]="CONN_WIFI_METERED";X[X.CONN_CELLULAR_5G]="CONN_CELLULAR_5G";X[X.CONN_DISCO]="CONN_DISCO";
X[X.CONN_CELLULAR_UNKNOWN]="CONN_CELLULAR_UNKNOWN";X[X.CONN_CELLULAR_4G]="CONN_CELLULAR_4G";X[X.CONN_CELLULAR_3G]="CONN_CELLULAR_3G";X[X.CONN_CELLULAR_2G]="CONN_CELLULAR_2G";X[X.CONN_WIFI]="CONN_WIFI";X[X.CONN_NONE]="CONN_NONE";X[X.CONN_UNKNOWN]="CONN_UNKNOWN";X[X.CONN_DEFAULT]="CONN_DEFAULT";
var Y={DETAILED_NETWORK_TYPE_NR_NSA:126,DETAILED_NETWORK_TYPE_NR_SA:125,DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED:124,DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT:123,DETAILED_NETWORK_TYPE_DISCONNECTED:122,DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN:121,DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN:120,DETAILED_NETWORK_TYPE_WIMAX:119,DETAILED_NETWORK_TYPE_ETHERNET:118,DETAILED_NETWORK_TYPE_BLUETOOTH:117,DETAILED_NETWORK_TYPE_WIFI:116,DETAILED_NETWORK_TYPE_LTE:115,DETAILED_NETWORK_TYPE_HSPAP:114,DETAILED_NETWORK_TYPE_EHRPD:113,
DETAILED_NETWORK_TYPE_EVDO_B:112,DETAILED_NETWORK_TYPE_UMTS:111,DETAILED_NETWORK_TYPE_IDEN:110,DETAILED_NETWORK_TYPE_HSUPA:109,DETAILED_NETWORK_TYPE_HSPA:108,DETAILED_NETWORK_TYPE_HSDPA:107,DETAILED_NETWORK_TYPE_EVDO_A:106,DETAILED_NETWORK_TYPE_EVDO_0:105,DETAILED_NETWORK_TYPE_CDMA:104,DETAILED_NETWORK_TYPE_1_X_RTT:103,DETAILED_NETWORK_TYPE_GPRS:102,DETAILED_NETWORK_TYPE_EDGE:101,DETAILED_NETWORK_TYPE_UNKNOWN:0};Y[Y.DETAILED_NETWORK_TYPE_NR_NSA]="DETAILED_NETWORK_TYPE_NR_NSA";
Y[Y.DETAILED_NETWORK_TYPE_NR_SA]="DETAILED_NETWORK_TYPE_NR_SA";Y[Y.DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED]="DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED";Y[Y.DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT]="DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT";Y[Y.DETAILED_NETWORK_TYPE_DISCONNECTED]="DETAILED_NETWORK_TYPE_DISCONNECTED";Y[Y.DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN";Y[Y.DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN";
Y[Y.DETAILED_NETWORK_TYPE_WIMAX]="DETAILED_NETWORK_TYPE_WIMAX";Y[Y.DETAILED_NETWORK_TYPE_ETHERNET]="DETAILED_NETWORK_TYPE_ETHERNET";Y[Y.DETAILED_NETWORK_TYPE_BLUETOOTH]="DETAILED_NETWORK_TYPE_BLUETOOTH";Y[Y.DETAILED_NETWORK_TYPE_WIFI]="DETAILED_NETWORK_TYPE_WIFI";Y[Y.DETAILED_NETWORK_TYPE_LTE]="DETAILED_NETWORK_TYPE_LTE";Y[Y.DETAILED_NETWORK_TYPE_HSPAP]="DETAILED_NETWORK_TYPE_HSPAP";Y[Y.DETAILED_NETWORK_TYPE_EHRPD]="DETAILED_NETWORK_TYPE_EHRPD";Y[Y.DETAILED_NETWORK_TYPE_EVDO_B]="DETAILED_NETWORK_TYPE_EVDO_B";
Y[Y.DETAILED_NETWORK_TYPE_UMTS]="DETAILED_NETWORK_TYPE_UMTS";Y[Y.DETAILED_NETWORK_TYPE_IDEN]="DETAILED_NETWORK_TYPE_IDEN";Y[Y.DETAILED_NETWORK_TYPE_HSUPA]="DETAILED_NETWORK_TYPE_HSUPA";Y[Y.DETAILED_NETWORK_TYPE_HSPA]="DETAILED_NETWORK_TYPE_HSPA";Y[Y.DETAILED_NETWORK_TYPE_HSDPA]="DETAILED_NETWORK_TYPE_HSDPA";Y[Y.DETAILED_NETWORK_TYPE_EVDO_A]="DETAILED_NETWORK_TYPE_EVDO_A";Y[Y.DETAILED_NETWORK_TYPE_EVDO_0]="DETAILED_NETWORK_TYPE_EVDO_0";Y[Y.DETAILED_NETWORK_TYPE_CDMA]="DETAILED_NETWORK_TYPE_CDMA";
Y[Y.DETAILED_NETWORK_TYPE_1_X_RTT]="DETAILED_NETWORK_TYPE_1_X_RTT";Y[Y.DETAILED_NETWORK_TYPE_GPRS]="DETAILED_NETWORK_TYPE_GPRS";Y[Y.DETAILED_NETWORK_TYPE_EDGE]="DETAILED_NETWORK_TYPE_EDGE";Y[Y.DETAILED_NETWORK_TYPE_UNKNOWN]="DETAILED_NETWORK_TYPE_UNKNOWN";var fu={LATENCY_PLAYER_RTSP:7,LATENCY_PLAYER_HTML5_INLINE:6,LATENCY_PLAYER_HTML5_FULLSCREEN:5,LATENCY_PLAYER_HTML5:4,LATENCY_PLAYER_FRAMEWORK:3,LATENCY_PLAYER_FLASH:2,LATENCY_PLAYER_EXO:1,LATENCY_PLAYER_UNKNOWN:0};fu[fu.LATENCY_PLAYER_RTSP]="LATENCY_PLAYER_RTSP";
fu[fu.LATENCY_PLAYER_HTML5_INLINE]="LATENCY_PLAYER_HTML5_INLINE";fu[fu.LATENCY_PLAYER_HTML5_FULLSCREEN]="LATENCY_PLAYER_HTML5_FULLSCREEN";fu[fu.LATENCY_PLAYER_HTML5]="LATENCY_PLAYER_HTML5";fu[fu.LATENCY_PLAYER_FRAMEWORK]="LATENCY_PLAYER_FRAMEWORK";fu[fu.LATENCY_PLAYER_FLASH]="LATENCY_PLAYER_FLASH";fu[fu.LATENCY_PLAYER_EXO]="LATENCY_PLAYER_EXO";fu[fu.LATENCY_PLAYER_UNKNOWN]="LATENCY_PLAYER_UNKNOWN";
var gu={LATENCY_AD_BREAK_TYPE_POSTROLL:3,LATENCY_AD_BREAK_TYPE_MIDROLL:2,LATENCY_AD_BREAK_TYPE_PREROLL:1,LATENCY_AD_BREAK_TYPE_UNKNOWN:0};gu[gu.LATENCY_AD_BREAK_TYPE_POSTROLL]="LATENCY_AD_BREAK_TYPE_POSTROLL";gu[gu.LATENCY_AD_BREAK_TYPE_MIDROLL]="LATENCY_AD_BREAK_TYPE_MIDROLL";gu[gu.LATENCY_AD_BREAK_TYPE_PREROLL]="LATENCY_AD_BREAK_TYPE_PREROLL";gu[gu.LATENCY_AD_BREAK_TYPE_UNKNOWN]="LATENCY_AD_BREAK_TYPE_UNKNOWN";var hu={LATENCY_ACTION_ERROR_STARTUP_TIMEOUT:1,LATENCY_ACTION_ERROR_UNSPECIFIED:0};
hu[hu.LATENCY_ACTION_ERROR_STARTUP_TIMEOUT]="LATENCY_ACTION_ERROR_STARTUP_TIMEOUT";hu[hu.LATENCY_ACTION_ERROR_UNSPECIFIED]="LATENCY_ACTION_ERROR_UNSPECIFIED";var iu={LIVE_STREAM_MODE_WINDOW:5,LIVE_STREAM_MODE_POST:4,LIVE_STREAM_MODE_LP:3,LIVE_STREAM_MODE_LIVE:2,LIVE_STREAM_MODE_DVR:1,LIVE_STREAM_MODE_UNKNOWN:0};iu[iu.LIVE_STREAM_MODE_WINDOW]="LIVE_STREAM_MODE_WINDOW";iu[iu.LIVE_STREAM_MODE_POST]="LIVE_STREAM_MODE_POST";iu[iu.LIVE_STREAM_MODE_LP]="LIVE_STREAM_MODE_LP";
iu[iu.LIVE_STREAM_MODE_LIVE]="LIVE_STREAM_MODE_LIVE";iu[iu.LIVE_STREAM_MODE_DVR]="LIVE_STREAM_MODE_DVR";iu[iu.LIVE_STREAM_MODE_UNKNOWN]="LIVE_STREAM_MODE_UNKNOWN";var ju={VIDEO_STREAM_TYPE_VOD:3,VIDEO_STREAM_TYPE_DVR:2,VIDEO_STREAM_TYPE_LIVE:1,VIDEO_STREAM_TYPE_UNSPECIFIED:0};ju[ju.VIDEO_STREAM_TYPE_VOD]="VIDEO_STREAM_TYPE_VOD";ju[ju.VIDEO_STREAM_TYPE_DVR]="VIDEO_STREAM_TYPE_DVR";ju[ju.VIDEO_STREAM_TYPE_LIVE]="VIDEO_STREAM_TYPE_LIVE";ju[ju.VIDEO_STREAM_TYPE_UNSPECIFIED]="VIDEO_STREAM_TYPE_UNSPECIFIED";
var ku={YT_IDB_TRANSACTION_TYPE_READ:2,YT_IDB_TRANSACTION_TYPE_WRITE:1,YT_IDB_TRANSACTION_TYPE_UNKNOWN:0};ku[ku.YT_IDB_TRANSACTION_TYPE_READ]="YT_IDB_TRANSACTION_TYPE_READ";ku[ku.YT_IDB_TRANSACTION_TYPE_WRITE]="YT_IDB_TRANSACTION_TYPE_WRITE";ku[ku.YT_IDB_TRANSACTION_TYPE_UNKNOWN]="YT_IDB_TRANSACTION_TYPE_UNKNOWN";var lu={PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN:2,PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT:1,PLAYER_ROTATION_TYPE_UNKNOWN:0};lu[lu.PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN]="PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN";
lu[lu.PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT]="PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT";lu[lu.PLAYER_ROTATION_TYPE_UNKNOWN]="PLAYER_ROTATION_TYPE_UNKNOWN";var mu="actionVisualElement spinnerInfo resourceInfo playerInfo commentInfo mdxInfo watchInfo thumbnailLoadInfo creatorInfo unpluggedInfo reelInfo subscriptionsFeedInfo requestIds mediaBrowserActionInfo musicLoadActionInfo shoppingInfo webViewInfo prefetchInfo accelerationSession commerceInfo webInfo tvInfo kabukiInfo mwebInfo musicInfo".split(" ");var nu=y.ytLoggingLatencyUsageStats_||{};z("ytLoggingLatencyUsageStats_",nu);function ou(){this.i=0}
function pu(){ou.i||(ou.i=new ou);return ou.i}
ou.prototype.tick=function(a,b,c,d){qu(this,"tick_"+a+"_"+b)||(c={timestamp:c,cttAuthInfo:d},M("web_csi_via_jspb")?(d=new Rj,D(d,1,a),D(d,2,b),a=new Uj,Zd(a,Rj,5,Vj,d),yr(a,c)):um("latencyActionTicked",{tickName:a,clientActionNonce:b},c))};
ou.prototype.info=function(a,b,c){var d=Object.keys(a).join("");qu(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,um("latencyActionInfo",a,{cttAuthInfo:c}))};
ou.prototype.jspbInfo=function(a,b,c){for(var d="",e=0;e<a.toJSON().length;e++)void 0!==a.toJSON()[e]&&(d=0===e?d.concat(""+e):d.concat("_"+e));qu(this,"info_"+d+"_"+b)||(D(a,2,b),b={cttAuthInfo:c},c=new Uj,Zd(c,Lj,7,Vj,a),yr(c,b))};
ou.prototype.span=function(a,b,c){var d=Object.keys(a).join("");qu(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,um("latencyActionSpan",a,{cttAuthInfo:c}))};
function qu(a,b){nu[b]=nu[b]||{count:0};var c=nu[b];c.count++;c.time=P();a.i||(a.i=fm(function(){var d=P(),e;for(e in nu)nu[e]&&6E4<d-nu[e].time&&delete nu[e];a&&(a.i=0)},0,5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new Q("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||Zr(c)),!0):!1}
;function ru(){var a=["ol"];Wt("").info.actionType="embed";a&&Fk("TIMING_AFT_KEYS",a);Fk("TIMING_ACTION","embed");su();a=Mt();var b=Ot();if("cold"===a.yt_lt||"cold"===b.loadType){var c=Ht(),d=Nt();d=d.gelTicks?d.gelTicks:d.gelTicks={};for(var e in c)e in d||Z(e,c[e]);e={};c=!1;d=p(Object.keys(a));for(var f=d.next();!f.done;f=d.next())f=f.value,(f=du(f,a[f]))&&!St(Ot(),f)&&(ut(b,f),ut(e,f),c=!0);c&&tu(e)}z("ytglobal.timingready_",!0);a=L("TIMING_ACTION");B("ytglobal.timingready_")&&a&&"_start"in Ht()&&
Gt()&&Rt()}
function uu(a,b,c,d){null!==b&&(Mt(c)[a]=b,(a=du(a,b,c))&&tu(a,c,d))}
function tu(a,b,c){if(!M("web_csi_via_jspb")||(void 0===c?0:c))c=Wt(b||""),ut(c.info,a),ut(Ot(b),a),c=Qt(b),b=Lt(b).cttAuthInfo,pu().info(a,c,b);else{c=new Lj;var d=Object.keys(a);a=Object.values(a);for(var e=0;e<d.length;e++){var f=d[e];try{switch(f){case "actionType":Nj(c,W[a[e]]);break;case "clientActionNonce":D(c,2,a[e]);break;case "clientScreenNonce":D(c,4,a[e]);break;case "loadType":D(c,3,a[e]);break;case "isPrewarmedLaunch":D(c,92,a[e]);break;case "isFirstInstall":D(c,55,a[e]);break;case "networkType":D(c,
5,eu[a[e]]);break;case "connectionType":D(c,26,X[a[e]]);break;case "detailedConnectionType":D(c,27,Y[a[e]]);break;case "isVisible":D(c,6,a[e]);break;case "playerType":D(c,7,fu[a[e]]);break;case "clientPlaybackNonce":D(c,8,a[e]);break;case "adClientPlaybackNonce":D(c,28,a[e]);break;case "previousCpn":D(c,77,a[e]);break;case "targetCpn":D(c,76,a[e]);break;case "isMonetized":D(c,9,a[e]);break;case "isPrerollAllowed":D(c,16,a[e]);break;case "isPrerollShown":D(c,17,a[e]);break;case "adType":D(c,12,a[e]);
break;case "adTypesAllowed":D(c,36,a[e]);break;case "adNetworks":D(c,37,a[e]);break;case "previousAction":D(c,13,W[a[e]]);break;case "isRedSubscriber":D(c,14,a[e]);break;case "serverTimeMs":D(c,15,a[e]);break;case "videoId":c.setVideoId(a[e]);break;case "adVideoId":D(c,20,a[e]);break;case "targetVideoId":D(c,78,a[e]);break;case "adBreakType":D(c,21,gu[a[e]]);break;case "isNavigation":Oj(c,a[e]);break;case "viewportHeight":D(c,29,a[e]);break;case "viewportWidth":D(c,30,a[e]);break;case "screenHeight":D(c,
84,a[e]);break;case "screenWidth":D(c,85,a[e]);break;case "browseId":D(c,31,a[e]);break;case "isCacheHit":D(c,32,a[e]);break;case "httpProtocol":D(c,33,a[e]);break;case "transportProtocol":D(c,34,a[e]);break;case "searchQuery":D(c,41,a[e]);break;case "isContinuation":D(c,42,a[e]);break;case "availableProcessors":D(c,43,a[e]);break;case "sdk":D(c,44,a[e]);break;case "isLocalStream":D(c,45,a[e]);break;case "navigationRequestedSameUrl":D(c,64,a[e]);break;case "shellStartupDurationMs":D(c,70,a[e]);break;
case "appInstallDataAgeMs":D(c,73,a[e]);break;case "latencyActionError":D(c,71,hu[a[e]]);break;case "actionStep":D(c,79,a[e]);break;case "jsHeapSizeLimit":D(c,80,a[e]);break;case "totalJsHeapSize":D(c,81,a[e]);break;case "usedJsHeapSize":D(c,82,a[e]);break;case "sourceVideoDurationMs":D(c,90,a[e]);break;case "videoOutputFrames":D(c,93,a[e]);break;case "isResume":D(c,104,a[e]);break;case "adPrebufferedTimeSecs":D(c,39,a[e]);break;case "isLivestream":D(c,47,a[e]);break;case "liveStreamMode":D(c,91,
iu[a[e]]);break;case "adCpn2":D(c,48,a[e]);break;case "adDaiDriftMillis":D(c,49,a[e]);break;case "videoStreamType":D(c,53,ju[a[e]]);break;case "playbackRequiresTap":D(c,56,a[e]);break;case "performanceNavigationTiming":D(c,67,a[e]);break;case "transactionType":D(c,74,ku[a[e]]);break;case "playerRotationType":D(c,101,lu[a[e]]);break;case "allowedPreroll":D(c,10,a[e]);break;case "shownPreroll":D(c,11,a[e]);break;case "getHomeRequestId":D(c,57,a[e]);break;case "getSearchRequestId":D(c,60,a[e]);break;
case "getPlayerRequestId":D(c,61,a[e]);break;case "getWatchNextRequestId":D(c,62,a[e]);break;case "getBrowseRequestId":D(c,63,a[e]);break;case "getLibraryRequestId":D(c,66,a[e]);break;default:mu.includes(f)&&Ok(new Q("Codegen laipb translator asked to translate message field",""+f))}}catch(g){Ok(Error("Codegen laipb translator failed to set "+f))}}vu(c,b)}}
function vu(a,b){Pt(b).push(a);Wt(b||"").jspbInfo.push(a);var c=Qt(b);b=Lt(b).cttAuthInfo;pu().jspbInfo(a,c,b)}
function Z(a,b,c){if(!b&&"_"!==a[0]){var d=a;S.mark&&(0==d.lastIndexOf("mark_",0)||(d="mark_"+d),c&&(d+=" ("+c+")"),S.mark(d))}d=Wt(c||"");d.tick[a]=b||P();if(d.callback&&d.callback[a]){d=p(d.callback[a]);for(var e=d.next();!e.done;e=d.next())e=e.value,e()}d=Nt(c);d.gelTicks&&(d.gelTicks[a]=!0);d=Ht(c);e=b||P();d[a]=e;e=Qt(c);var f=Lt(c).cttAuthInfo;if("_start"===a){var g=pu();qu(g,"baseline_"+e)||(b={timestamp:b,cttAuthInfo:f},M("web_csi_via_jspb")?(f=new Jj,D(f,1,e),e=new Uj,Zd(e,Jj,6,Vj,f),yr(e,
b)):um("latencyActionBaselined",{clientActionNonce:e},b))}else pu().tick(a,e,b,f);Rt(c);return d[a]}
function wu(){var a=Qt();requestAnimationFrame(function(){setTimeout(function(){a===Qt()&&Z("ol",void 0,void 0)},0)})}
function xu(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=gq+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function su(){function a(f){var g=It(),h=Kt(),k=L("CSI_START_TIMESTAMP_MILLIS",0);0<k&&!M("embeds_web_enable_csi_start_override_killswitch")&&(h=k);h&&(Z("srt",g.responseStart),1!==f.prerender&&Z("_start",h,void 0));f=Ut();0<f&&Z("fpt",f);f=It();f.isPerformanceNavigationTiming&&tu({performanceNavigationTiming:!0});Z("nreqs",f.requestStart,void 0);Z("nress",f.responseStart,void 0);Z("nrese",f.responseEnd,void 0);0<f.redirectEnd-f.redirectStart&&(Z("nrs",f.redirectStart,void 0),Z("nre",f.redirectEnd,
void 0));0<f.domainLookupEnd-f.domainLookupStart&&(Z("ndnss",f.domainLookupStart,void 0),Z("ndnse",f.domainLookupEnd,void 0));0<f.connectEnd-f.connectStart&&(Z("ntcps",f.connectStart,void 0),Z("ntcpe",f.connectEnd,void 0));f.secureConnectionStart>=Kt()&&0<f.connectEnd-f.secureConnectionStart&&(Z("nstcps",f.secureConnectionStart,void 0),Z("ntcpe",f.connectEnd,void 0));S&&"getEntriesByType"in S&&yu()}
var b=L("TIMING_INFO",{});if(M("web_csi_via_jspb")){b=zu(b);vu(b);b=Nj(Oj(new Lj,!0),W[cu(L("TIMING_ACTION"))]);var c=L("PREVIOUS_ACTION");c&&D(b,13,W[cu(c)]);(c=L("CLIENT_PROTOCOL"))&&D(b,33,c);(c=L("CLIENT_TRANSPORT"))&&D(b,34,c);(c=qs())&&"UNDEFINED_CSN"!==c&&D(b,4,c);c=xu();1!==c&&-1!==c||D(b,6,!0);c=Mt();Tt();D(b,3,"cold");a(c);c=Au();if(0<c.length){c=p(c);for(var d=c.next();!d.done;d=c.next()){d=d.value;var e=new Kj;D(e,1,d);ae(b,83,Kj,e)}}vu(b)}else{for(c in b)b.hasOwnProperty(c)&&uu(c,b[c]);
b={isNavigation:!0,actionType:cu(L("TIMING_ACTION"))};if(c=L("PREVIOUS_ACTION"))b.previousAction=cu(c);if(c=L("CLIENT_PROTOCOL"))b.httpProtocol=c;if(c=L("CLIENT_TRANSPORT"))b.transportProtocol=c;(c=qs())&&"UNDEFINED_CSN"!==c&&(b.clientScreenNonce=c);c=xu();if(1===c||-1===c)b.isVisible=!0;c=Mt();b.loadType="cold";a(c);c=Au();if(0<c.length)for(b.resourceInfo=[],c=p(c),d=c.next();!d.done;d=c.next())b.resourceInfo.push({resourceCache:d.value});tu(b)}}
function zu(a){var b=new Lj;a=p(Object.entries(a));for(var c=a.next();!c.done;c=a.next()){var d=p(c.value);c=d.next().value;d=d.next().value;switch(c){case "GetBrowse_rid":var e=new Qj;D(e,1,c);D(e,2,String(d));Pj(b,e);break;case "GetGuide_rid":e=new Qj;D(e,1,c);D(e,2,String(d));Pj(b,e);break;case "GetHome_rid":e=new Qj;D(e,1,c);D(e,2,String(d));Pj(b,e);break;case "GetPlayer_rid":e=new Qj;D(e,1,c);D(e,2,String(d));Pj(b,e);break;case "GetSearch_rid":e=new Qj;D(e,1,c);D(e,2,String(d));Pj(b,e);break;
case "GetSettings_rid":e=new Qj;D(e,1,c);D(e,2,String(d));Pj(b,e);break;case "GetTrending_rid":e=new Qj;D(e,1,c);D(e,2,String(d));Pj(b,e);break;case "GetWatchNext_rid":e=new Qj;D(e,1,c);D(e,2,String(d));Pj(b,e);break;case "yt_red":D(b,14,!!d);break;case "yt_ad":D(b,9,!!d)}}return b}
function Bu(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);ic()&&a.setAttribute("nonce",ic());return c?(a=S.getEntriesByName(c))&&a[0]&&(a=a[0],c=Kt(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function Au(){var a=[];if(document.querySelector&&S&&S.getEntriesByName)for(var b in Ft)if(Ft.hasOwnProperty(b)){var c=Ft[b];Bu(b,c)&&a.push(c)}return a}
function yu(){var a=window.location.protocol,b=S.getEntriesByType("resource");b=gb(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=ib(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Z("wffs",Jt(b.startTime)),Z("wffe",Jt(b.responseEnd)))}
var Cu=window;Cu.ytcsi&&(Cu.ytcsi.info=uu,Cu.ytcsi.tick=Z);var Du="tokens consistency mss client_location entities response_received_commands store PLAYER_PRELOAD".split(" "),Eu=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse"];function Fu(a,b,c,d){this.o=a;this.M=b;this.m=c;this.l=d;this.j=void 0;this.i=new Map;a.La||(a.La={});a.La=Object.assign({},tt,a.La)}
function Gu(a,b,c,d){if(void 0!==Fu.i){if(d=Fu.i,a=[a!==d.o,b!==d.M,c!==d.m,!1,!1,void 0!==d.j],a.some(function(e){return e}))throw new Q("InnerTubeTransportService is already initialized",a);
}else Fu.i=new Fu(a,b,c,d)}
function Hu(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?bt:c;var d=lt(b,a.o);if(!d)return Df(new Q("Error: No request builder found for command.",b));var e=d.o(b,void 0,c);return e?new yf(function(f){var g,h,k;return x(function(m){if(1==m.i){h="cors"===(null==(g=e.va)?void 0:g.mode)?"cors":void 0;if(a.m.ld){var q=e.config,r;q=null==q?void 0:null==(r=q.Ra)?void 0:r.sessionIndex;r=Ss({sessionIndex:q});k=Object.assign({},Iu(h),r);return m.u(2)}return v(m,Ju(e.config,
h),3)}2!=m.i&&(k=m.j);f(Ku(a,e,k));m.i=0})}):Df(new Q("Error: Failed to build request for command.",b))}
function Ku(a,b,c){var d,e,f,g,h,k,m,q,r,w,u,A,E,F,N,O,R,U,ca,lb,Xa,ja,H,ka,ma,Fe,Ge,wd,xd,yd;return x(function(va){switch(va.i){case 1:va.u(2);break;case 3:if((d=va.j)&&!d.isExpired())return va.return(Promise.resolve(d.i()));case 2:if(null==(e=b)?0:null==(f=e.ga)?0:f.context)for(g=p([]),h=g.next();!h.done;h=g.next())k=h.value,k.Eq(b.ga.context);if(null==(m=a.j)?0:m.Kq(b.input,b.ga))return va.return(a.j.Bq(b.input,b.ga));(w=null==(r=b.config)?void 0:r.Ba)&&a.i.has(w)&&M("web_memoize_inflight_requests")?
q=a.i.get(w):(u=JSON.stringify(b.ga),F=null!=(E=null==(A=b.va)?void 0:A.headers)?E:{},b.va=Object.assign({},b.va,{headers:Object.assign({},F,c)}),N=Object.assign({},b.va),"POST"===b.va.method&&(N=Object.assign({},N,{body:u})),(null==(O=b.config)?0:O.Wc)&&Z(b.config.Wc),R=function(){return a.M.fetch(b.input,N,b.config)},q=R(),w&&a.i.set(w,q));
return v(va,q,4);case 4:U=va.j;if(M("web_one_platform_error_handling")&&(null==(ca=U)?0:null==(lb=ca.error)?0:lb.details))for(Xa=U.error.details,ja=p(Xa),H=ja.next();!H.done;H=ja.next())ka=H.value,(ma=ka["@type"])&&-1<Eu.indexOf(ma)&&(delete ka["@type"],U=ka);w&&a.i.has(w)&&a.i.delete(w);(null==(Fe=b.config)?0:Fe.Xc)&&Z(b.config.Xc);if(U||null==(Ge=a.j)||!Ge.uq(b.input,b.ga)){va.u(5);break}return v(va,a.j.Aq(b.input,b.ga),6);case 6:U=va.j;case 5:if(U&&(null==(wd=U.Jq)||!wd.Mq)&&a.l)for(xd=p(Du),h=
xd.next();!h.done;h=xd.next())yd=h.value,a.l[yd]&&a.l[yd].handleResponse(U,b);return va.return(U)}})}
function Ju(a,b){var c,d,e,f;return x(function(g){if(1==g.i){e=null==(c=a)?void 0:null==(d=c.Ra)?void 0:d.sessionIndex;var h=Ss({sessionIndex:e});if(!(h instanceof yf)){var k=new yf(cb);zf(k,2,h);h=k}return v(g,h,2)}f=g.j;return g.return(Promise.resolve(Object.assign({},Iu(b),f)))})}
function Iu(a){var b={"Content-Type":"application/json"};L("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=L("EOM_VISITOR_DATA"):L("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=L("VISITOR_DATA"));M("track_webfe_innertube_auth_mismatch")&&(b["X-Youtube-Bootstrap-Logged-In"]=L("LOGGED_IN",!1));"cors"!==a&&((a=L("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=L("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=L("CHROME_CONNECTED_HEADER"))&&(b["X-Youtube-Chrome-Connected"]=
a),(a=L("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var Lu=new Us("INNERTUBE_TRANSPORT_TOKEN");var Mu=["share/get_web_player_share_panel"],Nu=["feedback"],Ou=["notification/modify_channel_preference"],Pu=["browse/edit_playlist"],Qu=["subscription/subscribe"],Ru=["subscription/unsubscribe"];function Su(){}
t(Su,qt);Su.prototype.l=function(){return Qu};
Su.prototype.i=function(a){return Es(a,zk)||void 0};
Su.prototype.j=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
ea.Object.defineProperties(Su.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Tu(){}
t(Tu,qt);Tu.prototype.l=function(){return Ru};
Tu.prototype.i=function(a){return Es(a,yk)||void 0};
Tu.prototype.j=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
ea.Object.defineProperties(Tu.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Uu(){}
t(Uu,qt);Uu.prototype.l=function(){return Nu};
Uu.prototype.i=function(a){return Es(a,fj)||void 0};
Uu.prototype.j=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
ea.Object.defineProperties(Uu.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Vu(){}
t(Vu,qt);Vu.prototype.l=function(){return Ou};
Vu.prototype.i=function(a){return Es(a,xk)||void 0};
Vu.prototype.j=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function Wu(){}
t(Wu,qt);Wu.prototype.l=function(){return Pu};
Wu.prototype.i=function(a){return Es(a,wk)||void 0};
Wu.prototype.j=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function Xu(){}
t(Xu,qt);Xu.prototype.l=function(){return Mu};
Xu.prototype.i=function(a){return Es(a,vk)};
Xu.prototype.j=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var Ws=new Us("NETWORK_SLI_TOKEN");function Yu(a){this.i=a}
Yu.prototype.fetch=function(a,b){var c=this,d,e;return x(function(f){c.i&&(d=mc(nc(5,Dc(a,"key")))||"/UNKNOWN_PATH",c.i.start(d));e=new window.Request(a,b);return M("web_fetch_promise_cleanup_killswitch")?f.return(Promise.resolve(fetch(e).then(function(g){return c.handleResponse(g)}).catch(function(g){Zr(g)}))):f.return(fetch(e).then(function(g){return c.handleResponse(g)}).catch(function(g){Zr(g)}))})};
Yu.prototype.handleResponse=function(a){var b=a.text().then(function(c){return JSON.parse(c.replace(")]}'",""))});
a.redirected||a.ok?this.i&&this.i.success():(this.i&&this.i.failure(),b=b.then(function(c){Zr(new Q("Error: API fetch failed",a.status,a.url,c));return Object.assign({},c,{errorMetadata:{status:a.status}})}));
return b};
Yu[Ts]=[new Vs];var Zu=new Us("NETWORK_MANAGER_TOKEN");var $u;function av(a){bo.call(this,1,arguments);this.csn=a}
t(av,bo);var lo=new co("screen-created",av),bv=[],dv=cv,ev=0;function fv(a,b,c,d,e,f,g){function h(){Zr(new Q("newScreen() parent element does not have a VE - rootVe",b))}
var k=dv();f=new js({veType:b,youtubeData:f,jspbYoutubeData:void 0});e={cttAuthInfo:e,ba:k};if(M("il_via_jspb")){var m=new yj;m.V(k);zj(m,f.getAsJspb());c&&c.visualElement?(f=new Aj,c.clientScreenNonce&&D(f,2,c.clientScreenNonce),Bj(f,c.visualElement.getAsJspb()),g&&D(f,4,Wj[g]),G(m,Aj,5,f)):c&&h();d&&D(m,3,d);Dr(m,e,a)}else f={csn:k,pageVe:f.getAsJson()},c&&c.visualElement?(f.implicitGesture={parentCsn:c.clientScreenNonce,gesturedVe:c.visualElement.getAsJson()},g&&(f.implicitGesture.gestureType=
g)):c&&h(),d&&(f.cloneCsn=d),a?tr("screenCreated",f,a,e):um("screenCreated",f,e);io(lo,new av(k));return k}
function gv(a,b,c,d){var e=d.filter(function(k){k.csn!==b?(k.csn=b,k=!0):k=!1;return k}),f={cttAuthInfo:ss(b),
ba:b};d=p(d);for(var g=d.next();!g.done;g=d.next())g=g.value.getAsJson(),(rb(g)||!g.trackingParams&&!g.veType)&&Zr(Error("Child VE logged with no data"));if(M("il_via_jspb")){var h=new Cj;h.V(b);Ej(h,c.getAsJspb());hb(e,function(k){k=k.getAsJspb();ae(h,3,tj,k)});
"UNDEFINED_CSN"==b?hv("visualElementAttached",h,f):Er(h,f,a)}else c={csn:b,parentVe:c.getAsJson(),childVes:hb(e,function(k){return k.getAsJson()})},"UNDEFINED_CSN"==b?hv("visualElementAttached",c,f):a?tr("visualElementAttached",c,a,f):um("visualElementAttached",c,f)}
function cv(){for(var a=Math.random()+"",b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}return fd(b,3)}
function hv(a,b,c){bv.push({payloadName:a,payload:b,options:c});ev||(ev=mo())}
function no(a){if(bv){for(var b=p(bv),c=b.next();!c.done;c=b.next())if(c=c.value,c.payload)if(M("il_via_jspb"))switch(c.payload.V(a.csn),c.payloadName){case "screenCreated":Dr(c.payload,c.options);break;case "visualElementAttached":Er(c.payload,c.options);break;case "visualElementShown":zr(c.payload,c.options);break;case "visualElementHidden":Ar(c.payload,c.options);break;case "visualElementGestured":Br(c.payload,c.options);break;case "visualElementStateChanged":Cr(c.payload,c.options);break;default:Zr(new Q("flushQueue unable to map payloadName to JSPB setter"))}else c.payload.csn=
a.csn,tr(c.payloadName,c.payload,null,c.options);bv.length=0}ev=0}
;function iv(){this.j=new Set;this.i=new Set;this.l=new Map}
iv.prototype.s=function(){};
iv.prototype.clear=function(){this.j.clear();this.i.clear();this.l.clear()};
Na(iv);function jv(){this.o=[];this.N=[];this.i=[];this.m=[];this.B=[];this.j=new Set;this.v=new Map}
jv.prototype.s=function(a){this.client=a};
function kv(a,b,c){c=void 0===c?0:c;b.then(function(d){a.j.has(c)&&a.l&&a.l();var e=qs(c),f=os(c);if(e&&f){var g;(null==d?0:null==(g=d.response)?0:g.trackingParams)&&gv(a.client,e,f,[ks(d.response.trackingParams)]);var h;(null==d?0:null==(h=d.playerResponse)?0:h.trackingParams)&&gv(a.client,e,f,[ks(d.playerResponse.trackingParams)])}})}
function lv(a,b,c,d){d=void 0===d?0:d;if(a.j.has(d))a.o.push([b,c]);else{var e=qs(d);c=c||os(d);e&&c&&gv(a.client,e,c,[b])}}
jv.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=void 0===c?0:c;if(d)if(c=qs(void 0===c?0:c)){a=this.client;var e=ks(d);d={cttAuthInfo:ss(c),ba:c};if(M("il_via_jspb")){var f=new Fj;f.V(c);e=e.getAsJspb();G(f,tj,2,e);D(f,4,Wj.INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK);b&&G(f,wj,3);"UNDEFINED_CSN"==c?hv("visualElementGestured",f,d):Br(f,d,a)}else f={csn:c,ve:e.getAsJson(),gestureType:"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK"},b&&(f.clientData=b),"UNDEFINED_CSN"==c?
hv("visualElementGestured",f,d):a?tr("visualElementGestured",f,a,d):um("visualElementGestured",f,d);b=!0}else b=!1;else b=!1;return b};
function mv(a,b,c){c=void 0===c?{}:c;a.j.add(c.layer||0);a.l=function(){nv(a,b,c);var f=os(c.layer);if(f){for(var g=p(a.o),h=g.next();!h.done;h=g.next())h=h.value,lv(a,h[0],h[1]||f,c.layer);f=p(a.N);for(g=f.next();!g.done;g=f.next()){var k=g.value;g=void 0;g=void 0===g?0:g;h=qs(g);var m=k[0]||os(g);if(h&&m){g=a.client;var q=k[1];k={cttAuthInfo:ss(h),ba:h};M("il_via_jspb")?(q=new Ij,q.V(h),m=m.getAsJspb(),G(q,tj,2,m),"UNDEFINED_CSN"==h?hv("visualElementStateChanged",q,k):Cr(q,k,g)):(m={csn:h,ve:m.getAsJson(),
clientData:q},"UNDEFINED_CSN"==h?hv("visualElementStateChanged",m,k):g?tr("visualElementStateChanged",m,g,k):um("visualElementStateChanged",m,k))}}}};
qs(c.layer)||a.l();if(c.Ob)for(var d=p(c.Ob),e=d.next();!e.done;e=d.next())kv(a,e.value,c.layer);else Yr(Error("Delayed screen needs a data promise."))}
function nv(a,b,c){c=void 0===c?{}:c;c.layer||(c.layer=0);var d=void 0!==c.Sc?c.Sc:c.layer;var e=qs(d);d=os(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=L("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var k=fv(a.client,b,f,c.Nb,c.cttAuthInfo,g,c.yq)}catch(m){as(m,{Hq:b,rootVe:d,parentVisualElement:void 0,wq:e,Dq:f,Nb:c.Nb});Yr(m);return}ts(k,b,
c.layer,c.cttAuthInfo);if(b=e&&"UNDEFINED_CSN"!==e&&d){a:{b=p(Object.values(is));for(f=b.next();!f.done;f=b.next())if(qs(f.value)===e){b=!0;break a}b=!1}b=!b}b&&(b=a.client,g=!0,h=(g=void 0===g?!1:g)?16:8,f={cttAuthInfo:ss(e),ba:e,Pb:g},M("il_via_jspb")?(h=new Gj,h.V(e),d=d.getAsJspb(),G(h,tj,2,d),D(h,4,g?16:8),"UNDEFINED_CSN"==e?hv("visualElementHidden",h,f):Ar(h,f,b)):(d={csn:e,ve:d.getAsJson(),eventType:h},"UNDEFINED_CSN"==e?hv("visualElementHidden",d,f):b?tr("visualElementHidden",d,b,f):um("visualElementHidden",
d,f)));a.i[a.i.length-1]&&!a.i[a.i.length-1].csn&&(a.i[a.i.length-1].csn=k||"");tu({clientScreenNonce:k});iv.getInstance().clear();d=os(c.layer);e&&"UNDEFINED_CSN"!==e&&d&&(M("web_mark_root_visible")||M("music_web_mark_root_visible"))&&(e=k,k={cttAuthInfo:ss(e),ba:e},M("il_via_jspb")?(b=new Hj,b.V(e),f=d.getAsJspb(),G(b,tj,2,f),D(b,4,1),"UNDEFINED_CSN"==e?hv("visualElementShown",b,k):zr(b,k)):(b={csn:e,ve:d.getAsJson(),eventType:1},"UNDEFINED_CSN"==e?hv("visualElementShown",b,k):um("visualElementShown",
b,k)));a.j.delete(c.layer||0);a.l=void 0;e=p(a.v);for(k=e.next();!k.done;k=e.next())b=p(k.value),k=b.next().value,b=b.next().value,b.has(c.layer)&&d&&lv(a,k,d,c.layer);for(c=0;c<a.m.length;c++){e=a.m[c];try{e()}catch(m){Yr(m)}}for(c=a.m.length=0;c<a.B.length;c++){e=a.B[c];try{e()}catch(m){Yr(m)}}}
;function ov(){var a,b;return x(function(c){if(1==c.i)return a=at().resolve(Lu),a?v(c,Hu(a),2):(Zr(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),c.return(void 0));if(b=c.j)return b.errorMetadata?(Zr(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),c.return(void 0)):c.return(b.xq);Zr(Error("Network request to get Datasync IDs failed."));return c.return(void 0)})}
;var pv=y.caches,qv;function rv(a){var b=a.indexOf(":");return-1===b?{Zb:a}:{Zb:a.substring(0,b),datasyncId:a.substring(b+1)}}
function sv(){return x(function(a){if(void 0!==qv)return a.return(qv);qv=new Promise(function(b){var c;return x(function(d){switch(d.i){case 1:return ya(d,2),v(d,pv.open("test-only"),4);case 4:return v(d,pv.delete("test-only"),5);case 5:za(d,3);break;case 2:if(c=Aa(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.i=0}})});
return a.return(qv)})}
function tv(a){var b,c,d,e,f,g,h;x(function(k){if(1==k.i)return v(k,sv(),2);if(3!=k.i){if(!k.j)return k.return(!1);b=[];return v(k,pv.keys(),3)}c=k.j;d=p(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=rv(f),h=g.datasyncId,!h||a.includes(h)||b.push(pv.delete(f));return k.return(Promise.all(b).then(function(m){return m.some(function(q){return q})}))})}
function uv(){var a,b,c,d,e,f,g;return x(function(h){if(1==h.i)return v(h,sv(),2);if(3!=h.i){if(!h.j)return h.return(!1);a=ym("cache contains other");return v(h,pv.keys(),3)}b=h.j;c=p(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=rv(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function vv(){try{return!!self.localStorage}catch(a){return!1}}
;function wv(a){a=a.match(/(.*)::.*::.*/);if(null!==a)return a[1]}
function xv(a){if(vv()){var b=Object.keys(window.localStorage);b=p(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=wv(c);void 0===d||a.includes(d)||self.localStorage.removeItem(c)}}}
function yv(){if(!vv())return!1;var a=ym(),b=Object.keys(window.localStorage);b=p(b);for(var c=b.next();!c.done;c=b.next())if(c=wv(c.value),void 0!==c&&c!==a)return!0;return!1}
;function zv(){ov().then(function(a){a&&(Jn(a),tv(a),xv(a))})}
function Av(){var a=new To;Xh.S(function(){var b,c,d,e;return x(function(f){switch(f.i){case 1:if(M("ytidb_clear_optimizations_killswitch")){f.u(2);break}b=ym("clear");if(b.startsWith("V")){var g=[b];Jn(g);tv(g);xv(g);return f.return()}c=yv();return v(f,uv(),3);case 3:return d=f.j,v(f,Kn(),4);case 4:if(e=f.j,!c&&!d&&!e)return f.return();case 2:a.L()?zv():a.m.add("publicytnetworkstatus-online",zv,!0,void 0,void 0),f.i=0}})})}
;function Bv(a){a&&(a.dataset?a.dataset[Cv("loaded")]="true":a.setAttribute("data-loaded","true"))}
function Dv(a,b){return a?a.dataset?a.dataset[Cv(b)]:a.getAttribute("data-"+b):null}
var Ev={};function Cv(a){return Ev[a]||(Ev[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Fv=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,Gv=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function Hv(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(Fv,""),c=c.replace(Gv,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else Iv(a,b,c)}
function Iv(a,b,c){c=void 0===c?null:c;var d=Jv(a),e=document.getElementById(d),f=e&&Dv(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=Aq(d,b),b=""+Ra(b),Kv[b]=f),g||(e=Lv(a,d,function(){Dv(e,"loaded")||(Bv(e),Dq(d),hl(Ya(Eq,d),0))},c)))}
function Lv(a,b,c,d){d=void 0===d?null:d;var e=kf("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Gh(e,Lb(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function Mv(a){a=Jv(a);var b=document.getElementById(a);b&&(Eq(a),b.parentNode.removeChild(b))}
function Nv(a,b){a&&b&&(a=""+Ra(b),(a=Kv[a])&&Cq(a))}
function Jv(a){var b=document.createElement("a");fc(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+kc(a)}
var Kv={};var Ov=[],Rv=!1;function Sv(){if(!M("disable_biscotti_fetch_for_ad_blocker_detection")&&!M("disable_biscotti_fetch_entirely_for_all_web_clients")&&Gs()){var a=L("PLAYER_VARS",{});if("1"!=tb(a)&&!Hs(a)){var b=function(){Rv=!0;"google_ad_status"in window?Fk("DCLKSTAT",1):Fk("DCLKSTAT",2)};
try{Hv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Ov.push(Xh.S(function(){if(!(Rv||"google_ad_status"in window)){try{Nv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Rv=!0;Fk("DCLKSTAT",3)}},5E3))}}}
function Tv(){var a=Number(L("DCLKSTAT",0));return isNaN(a)?0:a}
;function Uv(){this.state=1;this.i=null}
Uv.prototype.initialize=function(a,b,c){if(a.program){var d,e=null!=(d=a.interpreterScript)?d:null,f;d=null!=(f=a.interpreterUrl)?f:null;a.interpreterSafeScript&&(e=a.interpreterSafeScript,Db("From proto message. b/166824318"),e=e.privateDoNotAccessOrElseSafeScriptWrappedValue||"",e=(f=Ab())?f.createScript(e):e,e=(new Fb(e)).toString());a.interpreterSafeUrl&&(d=a.interpreterSafeUrl,Db("From proto message. b/166824318"),d=Lb(d.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||"").toString());
Vv(this,e,d,a.program,b,c)}else Zr(Error("Cannot initialize botguard without program"))};
function Vv(a,b,c,d,e,f){var g=void 0===g?"trayride":g;c?(a.state=2,Hv(c,function(){window[g]?Wv(a,d,g,e):(a.state=3,Mv(c),Zr(new Q("Unable to load Botguard","from "+c)))},f)):b?(f=kf("SCRIPT"),f.textContent=b,f.nonce=ic(),document.head.appendChild(f),document.head.removeChild(f),window[g]?Wv(a,d,g,e):(a.state=4,Zr(new Q("Unable to load Botguard from JS")))):Zr(new Q("Unable to load VM; no url or JS provided"))}
Uv.prototype.isInitialized=function(){return!!this.i};
function Wv(a,b,c,d){a.state=5;try{var e=new Ch({program:b,globalName:c});e.hd.then(function(){a.state=6;d&&d(b)});
Xv(a,e)}catch(f){a.state=7,f instanceof Error&&Zr(f)}}
Uv.prototype.invoke=function(a){a=void 0===a?{}:a;var b=this.i;if(b){var c={Mb:a};if(b.Wa)throw Error("Already disposed");a=Ah();var d;null!=(d=b.sa)&&d.j.i.Cb("/client_streamz/bg/fsc",d.Ba);d=b.md([c.Mb,c.kd]);null!=(b=b.sa)&&(a=Ah()-a,b.l.i.hb("/client_streamz/bg/fsl",a,b.Ba));b=d}else b=null;return b};
Uv.prototype.dispose=function(){Xv(this,null);this.state=8};
function Xv(a,b){pe(a.i);a.i=b}
;var Yv=new Uv;function Zv(){return Yv.isInitialized()}
function $v(a){a=void 0===a?{}:a;return Yv.invoke(a)}
;function aw(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?jm():d;this.m=c;this.l=d;this.j=new Bh;this.i=a;a={};c=p(this.i.entries());for(d=c.next();!d.done;a={Ca:a.Ca,Na:a.Na},d=c.next()){var e=p(d.value);d=e.next().value;e=e.next().value;a.Na=d;a.Ca=e;d=function(f){return function(){f.Ca.tb();b.i[f.Na].eb=!0;b.i.every(function(g){return!0===g.eb})&&b.j.resolve()}}(a);
e=fm(d,bw(this,a.Ca));this.i[a.Na]=Object.assign({},a.Ca,{tb:d,Za:e})}}
function cw(a){var b=Array.from(a.i.keys()).sort(function(d,e){return bw(a,a.i[e])-bw(a,a.i[d])});
b=p(b);for(var c=b.next();!c.done;c=b.next())c=a.i[c.value],void 0===c.Za||c.eb||(a.l.fa(c.Za),fm(c.tb,10))}
aw.prototype.cancel=function(){for(var a=p(this.i),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.Za||b.eb||this.l.fa(b.Za),b.eb=!0;this.j.resolve()};
function bw(a,b){var c;return null!=(c=b.priority)?c:a.m}
;function dw(a){this.state=a;this.plugins=[];this.s=void 0}
dw.prototype.install=function(){this.plugins.push.apply(this.plugins,ha(Ja.apply(0,arguments)))};
dw.prototype.transition=function(a,b){var c=this,d=this.B.find(function(f){return f.from===c.state&&f.F===a});
if(d){this.l&&(cw(this.l),this.l=void 0);this.state=a;d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(ew(this,e,this.s),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function ew(a,b,c){return function(){var d=Ja.apply(0,arguments),e=b.filter(function(k){var m;return 10===(null!=(m=null!=c?c:k.priority)?m:0)}),f=b.filter(function(k){var m;
return 10!==(null!=(m=null!=c?c:k.priority)?m:0)});
jm();var g={};e=p(e);for(var h=e.next();!h.done;g={Oa:g.Oa},h=e.next())g.Oa=h.value,hm(function(k){return function(){k.Oa.callback.apply(k.Oa,ha(d))}}(g));
f=f.map(function(k){var m;return{tb:function(){k.callback.apply(k,ha(d))},
priority:null!=(m=null!=c?c:k.priority)?m:0}});
f.length&&(a.l=new aw(f))}}
ea.Object.defineProperties(dw.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function fw(a){dw.call(this,void 0===a?"document_active":a);var b=this;this.s=10;this.i=new Map;this.B=[{from:"document_active",F:"document_disposed_preventable",action:this.N},{from:"document_active",F:"document_disposed",action:this.m},{from:"document_disposed_preventable",F:"document_disposed",action:this.m},{from:"document_disposed_preventable",F:"flush_logs",action:this.o},{from:"document_disposed_preventable",F:"document_active",action:this.j},{from:"document_disposed",F:"flush_logs",action:this.o},
{from:"document_disposed",F:"document_active",action:this.j},{from:"document_disposed",F:"document_disposed",action:function(){}},
{from:"flush_logs",F:"document_active",action:this.j}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
t(fw,dw);fw.prototype.N=function(a,b){if(!this.i.get("document_disposed_preventable")){a(null==b?void 0:b.event);var c,d;if((null==b?0:null==(c=b.event)?0:c.defaultPrevented)||(null==b?0:null==(d=b.event)?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.i=new Map;this.transition("document_active");return}}this.i.set("document_disposed_preventable",!0);this.i.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
fw.prototype.m=function(a,b){this.i.get("document_disposed")?this.transition("document_active"):(a(null==b?void 0:b.event),this.i.set("document_disposed",!0),this.transition("flush_logs"))};
fw.prototype.o=function(a,b){a(null==b?void 0:b.event);this.transition("document_active")};
fw.prototype.j=function(){this.i=new Map};function gw(a){dw.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.B=[{from:"document_visibility_unknown",F:"document_visible",action:this.j},{from:"document_visibility_unknown",F:"document_hidden",action:this.i},{from:"document_visibility_unknown",F:"document_foregrounded",action:this.o},{from:"document_visibility_unknown",F:"document_backgrounded",action:this.m},{from:"document_visible",F:"document_hidden",action:this.i},{from:"document_visible",F:"document_foregrounded",action:this.o},
{from:"document_visible",F:"document_visible",action:this.j},{from:"document_foregrounded",F:"document_visible",action:this.j},{from:"document_foregrounded",F:"document_hidden",action:this.i},{from:"document_foregrounded",F:"document_foregrounded",action:this.o},{from:"document_hidden",F:"document_visible",action:this.j},{from:"document_hidden",F:"document_backgrounded",action:this.m},{from:"document_hidden",F:"document_hidden",action:this.i},{from:"document_backgrounded",F:"document_hidden",action:this.i},
{from:"document_backgrounded",F:"document_backgrounded",action:this.m},{from:"document_backgrounded",F:"document_visible",action:this.j}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
M("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
t(gw,dw);gw.prototype.j=function(a,b){a(null==b?void 0:b.event);M("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
gw.prototype.i=function(a,b){a(null==b?void 0:b.event);M("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
gw.prototype.m=function(a,b){a(null==b?void 0:b.event)};
gw.prototype.o=function(a,b){a(null==b?void 0:b.event)};function hw(){this.i=new fw;this.j=new gw}
hw.prototype.install=function(){var a=Ja.apply(0,arguments);this.i.install.apply(this.i,ha(a));this.j.install.apply(this.j,ha(a))};function iw(){hw.call(this);var a={};this.install((a.document_disposed={callback:this.l},a));a={};this.install((a.flush_logs={callback:this.m},a))}
var jw;t(iw,hw);iw.prototype.m=function(){if(M("web_fp_via_jspb")){var a=new sj,b=qs();b&&a.V(b);b=new Uj;Zd(b,sj,380,Vj,a);yr(b);M("web_fp_via_jspb_and_json")&&um("finalPayload",{csn:qs()})}else um("finalPayload",{csn:qs()})};
iw.prototype.l=function(){cs(ds)};function kw(){}
kw.getInstance=function(){var a=B("ytglobal.storage_");a||(a=new kw,z("ytglobal.storage_",a));return a};
kw.prototype.estimate=function(){var a,b,c;return x(function(d){a=navigator;return(null==(b=a.storage)?0:b.estimate)?d.return(a.storage.estimate()):(null==(c=a.webkitTemporaryStorage)?0:c.queryUsageAndQuota)?d.return(lw()):d.return()})};
function lw(){var a=navigator;return new Promise(function(b,c){var d;null!=(d=a.webkitTemporaryStorage)&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
z("ytglobal.storageClass_",kw);function sm(a,b){var c=this;this.handleError=a;this.i=b;this.j=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.j=!0});
this.l=Math.random()<=Ik("ytidb_transaction_ended_event_rate_limit",.02)}
sm.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":M("idb_data_corrupted_killswitch")||this.i("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.i("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":M("idb_is_supported_completed_killswitch")||this.i("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":mw(this,b);break;case "TRANSACTION_ENDED":this.l&&this.i("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign({},b,
{hasWindowUnloaded:this.j}),this.i("idbTransactionAborted",a)}};
function mw(a,b){kw.getInstance().estimate().then(function(c){c=Object.assign({},b,{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:nw(null==c?void 0:c.usage),deviceStorageQuotaMbytes:nw(null==c?void 0:c.quota)});a.i("idbQuotaExceeded",c)})}
function nw(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;function ow(a,b,c){J.call(this);var d=this;c=c||L("POST_MESSAGE_ORIGIN")||window.document.location.protocol+"//"+window.document.location.hostname;this.l=b||null;this.targetOrigin="*";this.m=c;this.sessionId=null;this.channel="widget";this.G=!!a;this.v=function(e){a:if(!("*"!=d.m&&e.origin!=d.m||d.l&&e.source!=d.l||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.G&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.m=d.targetOrigin=e.origin);d.l=e.source;d.sessionId=f.id;d.j&&(d.j(),d.j=null);break;case "command":d.o&&(!d.s||0<=eb(d.s,f.func))&&d.o(f.func,f.args,e.origin)}}};
this.s=this.j=this.o=null;window.addEventListener("message",this.v)}
t(ow,J);ow.prototype.sendMessage=function(a,b){if(b=b||this.l){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){Pk(d)}}};
ow.prototype.C=function(){window.removeEventListener("message",this.v);J.prototype.C.call(this)};function pw(){this.j=[];this.isReady=!1;this.l={};var a=this.i=new ow(!!L("WIDGET_ID_ENFORCE")),b=this.Uc.bind(this);a.o=b;a.s=null;this.i.channel="widget";if(a=L("WIDGET_ID"))this.i.sessionId=a}
l=pw.prototype;l.Uc=function(a,b,c){"addEventListener"===a&&b?(a=b[0],this.l[a]||"onReady"===a||(this.addEventListener(a,qw(this,a)),this.l[a]=!0)):this.Db(a,b,c)};
l.Db=function(){};
function qw(a,b){return function(c){return a.sendMessage(b,c)}}
l.addEventListener=function(){};
l.Hc=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.pb());this.sendMessage("onReady");fb(this.j,this.ic,this);this.j=[]};
l.pb=function(){return null};
function rw(a,b){a.sendMessage("infoDelivery",b)}
l.ic=function(a){this.isReady?this.i.sendMessage(a):this.j.push(a)};
l.sendMessage=function(a,b){this.ic({event:a,info:void 0===b?null:b})};
l.dispose=function(){this.i=null};var sw=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function tw(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function uw(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=p(sw);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function vw(a,b,c,d){if(Qa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function ww(a){pw.call(this);this.listeners=[];this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.ed.bind(this));this.addEventListener("onVolumeChange",this.fd.bind(this));this.addEventListener("onApiChange",this.Yc.bind(this));this.addEventListener("onPlaybackQualityChange",this.bd.bind(this));this.addEventListener("onPlaybackRateChange",this.cd.bind(this));this.addEventListener("onStateChange",this.dd.bind(this));this.addEventListener("onWebglSettingsChanged",
this.gd.bind(this))}
t(ww,pw);l=ww.prototype;
l.Db=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&tw(a)){var d=b;if(Qa(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=uw(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=uw(e);break;case "loadPlaylist":case "cuePlaylist":e=vw(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);tw(a)&&rw(this,this.pb())}};
l.onReady=function(){var a=this.Hc.bind(this);this.i.j=a;a=this.api.getVideoData();!1===a.isPlayable&&this.sendMessage("onError",a.errorCode)};
l.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
l.pb=function(){if(!this.api)return null;var a=this.api.getApiInterface();mb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
l.dd=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());rw(this,a)};
l.bd=function(a){rw(this,{playbackQuality:a})};
l.cd=function(a){rw(this,{playbackRate:a})};
l.Yc=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],m=this.api.getOption(e,k);b[e][k]=m}}this.sendMessage("apiInfoDelivery",b)};
l.fd=function(){rw(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
l.ed=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());rw(this,a)};
l.gd=function(){var a={sphericalProperties:this.api.getSphericalProperties()};rw(this,a)};
l.dispose=function(){pw.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function xw(a){J.call(this);this.j={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.cc,this)}
t(xw,J);l=xw.prototype;l.start=function(){this.started||this.i()||(this.started=!0,this.connection.wa("RECEIVING"))};
l.wa=function(a,b){this.started&&!this.i()&&this.connection.wa(a,b)};
l.cc=function(a,b,c){if(this.started&&!this.i()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=yw(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=zw(a,c))&&this.wa(a,c))}}};
l.addListener=function(a){if(!(a in this.j)){var b=this.Zc.bind(this,a);this.j[a]=b;this.addEventListener(a,b)}};
l.Zc=function(a,b){this.started&&!this.i()&&this.connection.wa(a,this.ob(a,b))};
l.ob=function(a,b){if(null!=b)return{value:b}};
l.removeListener=function(a){a in this.j&&(this.removeEventListener(a,this.j[a]),delete this.j[a])};
l.C=function(){var a=this.connection;a.i()||vi(a.j,"command",this.cc,this);this.connection=null;for(var b in this.j)this.j.hasOwnProperty(b)&&this.removeListener(b);J.prototype.C.call(this)};function Aw(a,b){xw.call(this,b);this.api=a;this.start()}
t(Aw,xw);Aw.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
Aw.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function yw(a,b){switch(a){case "loadVideoById":return a=uw(b),[a];case "cueVideoById":return a=uw(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=vw(b),[a];case "cuePlaylist":return a=vw(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function zw(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Aw.prototype.ob=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return xw.prototype.ob.call(this,a,b)};
Aw.prototype.C=function(){xw.prototype.C.call(this);delete this.api};function Bw(a){a=void 0===a?!1:a;J.call(this);this.j=new K(a);re(this,this.j)}
Za(Bw,J);Bw.prototype.subscribe=function(a,b,c){return this.i()?0:this.j.subscribe(a,b,c)};
Bw.prototype.m=function(a,b){this.i()||this.j.qa.apply(this.j,arguments)};function Cw(a,b,c){Bw.call(this);this.l=a;this.destination=b;this.id=c}
t(Cw,Bw);Cw.prototype.wa=function(a,b){this.i()||this.l.wa(this.destination,this.id,a,b)};
Cw.prototype.C=function(){this.destination=this.l=null;Bw.prototype.C.call(this)};function Dw(a,b,c){J.call(this);this.destination=a;this.origin=c;this.j=nq(window,"message",this.l.bind(this));this.connection=new Cw(this,a,b);re(this,this.connection)}
t(Dw,J);Dw.prototype.wa=function(a,b,c,d){this.i()||a!==this.destination||(a={id:b,command:c},d&&(a.data=d),this.destination.postMessage(JSON.stringify(a),this.origin))};
Dw.prototype.l=function(a){if(!this.i()&&a.origin===this.origin){var b=a.data;if("string"===typeof b){try{b=JSON.parse(b)}catch(d){return}if(b.command){var c=this.connection;c.i()||c.m("command",b.command,b.data,a.origin)}}}};
Dw.prototype.C=function(){oq(this.j);this.destination=null;J.prototype.C.call(this)};function Ew(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||vb(b);this.assets=a.assets||{};this.attrs=a.attrs||vb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Ew.prototype.clone=function(){var a=new Ew,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Oa(c)?a[b]=vb(c):a[b]=c}return a};var Fw=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function Gw(a){a=a||"";if(window.spf){var b=a.match(Fw);spf.style.load(a,b?b[1]:"",void 0)}else Hw(a)}
function Hw(a){var b=Iw(a),c=document.getElementById(b),d=c&&Dv(c,"loaded");d||c&&!d||(c=Jw(a,b,function(){Dv(c,"loaded")||(Bv(c),Dq(b),hl(Ya(Eq,b),0))}))}
function Jw(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Lb(a);gc(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function Iw(a){var b=kf("A");Db("This URL is never added to the DOM");fc(b,new Ob(a,Pb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+kc(a)}
;function Kw(){J.call(this);this.j=[]}
t(Kw,J);Kw.prototype.C=function(){for(;this.j.length;){var a=this.j.pop();a.target.removeEventListener(a.name,a.callback,void 0)}J.prototype.C.call(this)};function Lw(){Kw.apply(this,arguments)}
t(Lw,Kw);function Mw(a,b,c,d){J.call(this);var e=this;this.v=b;this.webPlayerContextConfig=d;this.da=!1;this.api={};this.W=this.s=null;this.K=new K;this.j={};this.R=this.X=this.elementId=this.ra=this.config=null;this.P=!1;this.m=this.G=null;this.ka={};this.Pa=["onReady"];this.lastError=null;this.Ea=NaN;this.J={};this.Qa=new Lw(this);this.T=0;this.l=this.o=a;re(this,this.K);Nw(this);Ow(this);re(this,this.Qa);c?this.T=hl(function(){e.loadNewVideoConfig(c)},0):d&&(Pw(this),Qw(this))}
t(Mw,J);l=Mw.prototype;l.getId=function(){return this.v};
l.loadNewVideoConfig=function(a){if(!this.i()){this.T&&(il(this.T),this.T=0);var b=a||{};b instanceof Ew||(b=new Ew(b));this.config=b;this.setConfig(a);Qw(this);this.isReady()&&Rw(this)}};
function Pw(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;"video-player"===a.elementId&&(a.elementId=a.v,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.v:a.config.attrs.id=a.v);var c;(null==(c=a.l)?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
l.setConfig=function(a){this.ra=a;this.config=Sw(a);Pw(this);if(!this.X){var b;this.X=Tw(this,(null==(b=this.config.args)?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null==(c=this.config)?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.l&&(this.l.style.width=Qh(Number(b)||b)),(a=a.height)&&this.l&&(this.l.style.height=Qh(Number(a)||a))};
function Rw(a){if(a.config&&!0!==a.config.loaded)if(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay){var b;a.api.loadVideoByPlayerVars(null!=(b=a.config.args)?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function Uw(a){var b=!0,c=Vw(a);c&&a.config&&(a=Ww(a),b=Dv(c,"version")===a);return b&&!!B("yt.player.Application.create")}
function Qw(a){if(!a.i()&&!a.P){var b=Uw(a);if(b&&"html5"===(Vw(a)?"html5":null))a.R="html5",a.isReady()||Xw(a);else if(Yw(a),a.R="html5",b&&a.m&&a.o)a.o.appendChild(a.m),Xw(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.G=function(){c=!0;var d=Zw(a,"player_bootstrap_method")?B("yt.player.Application.createAlternate")||B("yt.player.Application.create"):B("yt.player.Application.create");var e=a.config?Sw(a.config):void 0;d&&d(a.o,e,a.webPlayerContextConfig);Xw(a)};
a.P=!0;b?a.G():(Hv(Ww(a),a.G),(b=$w(a))&&Gw(b),ax(a)&&!c&&z("yt.player.Application.create",null))}}}
function Vw(a){var b=jf(a.elementId);!b&&a.l&&a.l.querySelector&&(b=a.l.querySelector("#"+a.elementId));return b}
function Xw(a){if(!a.i()){var b=Vw(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.P=!1;if(!Zw(a,"html5_remove_not_servable_check_killswitch")){var d;if((null==b?0:b.isNotServable)&&a.config&&(null==b?0:b.isNotServable(null==(d=a.config.args)?void 0:d.video_id)))return}bx(a)}else a.Ea=hl(function(){Xw(a)},50)}}
function bx(a){Nw(a);a.da=!0;var b=Vw(a);if(b){a.s=cx(a,b,"addEventListener");a.W=cx(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=cx(a,b,f))}}for(var g in a.j)a.j.hasOwnProperty(g)&&a.s&&a.s(g,a.j[g]);Rw(a);a.X&&a.X(a.api);a.K.qa("onReady",a.api)}
function cx(a,b,c){var d=b[c];return function(){var e=Ja.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,Zr(f))}}}
function Nw(a){a.da=!1;if(a.W)for(var b in a.j)a.j.hasOwnProperty(b)&&a.W(b,a.j[b]);for(var c in a.J)a.J.hasOwnProperty(c)&&il(Number(c));a.J={};a.s=null;a.W=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.ra};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
l.isReady=function(){return this.da};
function Ow(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){Dq("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){Dq("WATCH_LATER_VIDEO_REMOVED",b)})}
l.addEventListener=function(a,b){var c=this,d=Tw(this,b);d&&(0<=eb(this.Pa,a)||this.j[a]||(b=dx(this,a),this.s&&this.s(a,b)),this.K.subscribe(a,d),"onReady"===a&&this.isReady()&&hl(function(){d(c.api)},0))};
l.removeEventListener=function(a,b){this.i()||(b=Tw(this,b))&&vi(this.K,a,b)};
function Tw(a,b){var c=b;if("string"===typeof b){if(a.ka[b])return a.ka[b];c=function(){var d=Ja.apply(0,arguments),e=B(b);if(e)try{e.apply(y,d)}catch(f){Yr(f)}};
a.ka[b]=c}return c?c:null}
function dx(a,b){var c="ytPlayer"+b+a.v;a.j[b]=c;y[c]=function(d){var e=hl(function(){if(!a.i()){try{a.K.qa(b,null!=d?d:void 0)}catch(h){Zr(new Q("PlayerProxy error when creating global callback",{error:h,event:b,playerId:a.v,data:d}))}var f=a.J,g=String(e);g in f&&delete f[g]}},0);
sb(a.J,String(e))};
return c}
l.getPlayerType=function(){return this.R||(Vw(this)?"html5":null)};
l.getLastError=function(){return this.lastError};
function Yw(a){a.cancel();Nw(a);a.R=null;a.config&&(a.config.loaded=!1);var b=Vw(a);b&&(Uw(a)||!ax(a)?a.m=b:(b&&b.destroy&&b.destroy(),a.m=null));if(a.o)for(a=a.o;b=a.firstChild;)a.removeChild(b)}
l.cancel=function(){this.G&&Nv(Ww(this),this.G);il(this.Ea);this.P=!1};
l.C=function(){Yw(this);if(this.m&&this.config&&this.m.destroy)try{this.m.destroy()}catch(b){Yr(b)}this.ka=null;for(var a in this.j)this.j.hasOwnProperty(a)&&(y[this.j[a]]=null);this.ra=this.config=this.api=null;delete this.o;delete this.l;J.prototype.C.call(this)};
function ax(a){var b,c;a=null==(b=a.config)?void 0:null==(c=b.args)?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function Ww(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function $w(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Zw(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if(null==(d=a.config)?0:d.args)c=a.config.args.fflags}return"true"===Vk(c||"","&")[b]}
function Sw(a){for(var b={},c=p(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?vb(e):e}return b}
;var ex={},fx="player_uid_"+(1E9*Math.random()>>>0);function gx(a,b,c){var d="player";c=void 0===c?!0:c;d="string"===typeof d?jf(d):d;var e=fx+"_"+Ra(d),f=ex[e];if(f&&c)return hx(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new Mw(d,e,a,b);ex[e]=f;Dq("player-added",f.api);se(f,function(){delete ex[f.getId()]});
return f.api}
function hx(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var ix=null,jx=null,kx=null;function lx(){mx()}
function nx(){mx()}
function mx(){var a=ix.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
;function ox(a,b,c){a="ST-"+kc(a).toString(36);b=b?tc(b):"";c=c||5;Gs()&&yl(a,b,c)}
;function px(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=L("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=L("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=oc(window.location.href);g&&f.push(g);g=oc(d);if(0<=eb(f,g)||!g&&0==d.lastIndexOf("/",0))if(M("autoescape_tempdata_url")&&(f=document.createElement("a"),fc(f,d),d=f.href),d&&(d=pc(d),f=d.indexOf("#"),d=0>f?d:d.slice(0,f)))if(e&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:qs()},b)),h){var h=parseInt(h,10);isFinite(h)&&0<h&&
ox(d,b,h)}else ox(d,b)}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var k=void 0===k?{}:k;var m=void 0===m?"":m;var q=void 0===q?window:q;c=q.location;a=vc(a,k)+m;var r=void 0===r?Ph:r;a:{r=void 0===r?Ph:r;for(k=0;k<r.length;++k)if(m=r[k],m instanceof Nh&&m.isValid(a)){r=new Ob(a,Pb);break a}r=void 0}r=r||Sb;if(r instanceof Ob)var w=Qb(r);else{a:if(Fh){try{w=new URL(r)}catch(u){w="https:";break a}w=w.protocol}else b:{w=document.createElement("a");try{w.href=r}catch(u){w=void 0;
break b}w=-1!==[":",""].indexOf(w.protocol)?"https:":w.protocol}w="javascript:"===w?"about:invalid":r}c.href=w}return!0}
;z("yt.setConfig",Fk);z("yt.config.set",Fk);z("yt.setMsg",vs);z("yt.msgs.set",vs);z("yt.logging.errors.log",Yr);
z("writeEmbed",function(){var a=L("PLAYER_CONFIG");if(!a){var b=L("PLAYER_VARS");b&&(a={args:b})}Qs(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=L("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);M("embeds_js_api_set_1p_cookie")&&(c=$k(window.location.href),c.embedsTokenValue&&(a.args.embedsTokenValue=c.embedsTokenValue));ru();if((c=L("WEB_PLAYER_CONTEXT_CONFIGS"))&&
"WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER"in c){c=c.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=$k(window.location.href);d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}ix=gx(a,c,!1)}else ix=gx(a);ix.addEventListener("onVideoDataChange",lx);ix.addEventListener("onReady",nx);a=L("POST_MESSAGE_ID","player");L("ENABLE_JS_API")?kx=new ww(ix):L("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(jx=new Dw(window.parent,
a,b),kx=new Aw(ix,jx.connection));Sv();M("ytidb_create_logger_embed_killswitch")||rm();a={};jw||(jw=new iw);jw.install((a.flush_logs={callback:function(){Zq()}},a));
M("embeds_web_enable_new_nwl")?$o():hp();M("ytidb_clear_embedded_player")&&Xh.S(function(){var e;if(!$u){var f=at(),g={xb:Zu,mc:Yu};f.providers.set(g.xb,g);g={Lb:{feedbackEndpoint:mt(Uu),modifyChannelNotificationPreferenceEndpoint:mt(Vu),playlistEditEndpoint:mt(Wu),subscribeEndpoint:mt(Su),unsubscribeEndpoint:mt(Tu),webPlayerShareEntityServiceEndpoint:mt(Xu)}};var h=M("web_enable_client_location_service")?ht.getInstance():void 0,k={};h&&(k.client_location=h);if(void 0===m){Rs.i||(Rs.i=new Rs);var m=
Rs.i}void 0===e&&(e=f.resolve(Zu));Gu(g,e,m,k);m={xb:Lu,nc:Fu.i};f.providers.set(m.xb,m);$u=f.resolve(Lu)}Av()})});
var qx=Nk(function(){wu();var a=Bl.getInstance(),b=El(119),c=1<window.devicePixelRatio;if(document.body&&ii(document.body,"exp-invert-logo"))if(c&&!ii(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!ii(d,"inverted-hdpi")){var e=gi(d);hi(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&ii(document.body,"inverted-hdpi")&&ji();if(b!=c){b="f"+(Math.floor(119/31)+1);d=Fl(b)||0;d=c?d|67108864:d&-67108865;0==d?delete Al[b]:(c=d.toString(16),
Al[b]=c.toString());c=!0;M("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.i;d=[];for(var f in Al)d.push(f+"="+encodeURIComponent(String(Al[f])));yl(b,d.join("&"),63072E3,a.j,c)}jv.i||(jv.i=new jv);a=jv.i;f=16623;var g=void 0===g?{}:g;Object.values(ws).includes(f)||(Zr(new Q("createClientScreen() called with a non-page VE",f)),f=83769);g.isHistoryNavigation||a.i.push({rootVe:f,key:g.key||""});a.o=[];a.N=[];g.Ob?mv(a,f,g):nv(a,f,g)}),rx=Nk(function(){ix&&ix.sendAbandonmentPing&&ix.sendAbandonmentPing();
L("PL_ATT")&&Yv.dispose();for(var a=Xh,b=0,c=Ov.length;b<c;b++)a.fa(Ov[b]);Ov.length=0;Mv("//static.doubleclick.net/instream/ad_status.js");Rv=!1;Fk("DCLKSTAT",0);qe(kx,jx);ix&&(ix.removeEventListener("onVideoDataChange",lx),ix.destroy())});
window.addEventListener?(window.addEventListener("load",qx),window.addEventListener("pagehide",rx)):window.attachEvent&&(window.attachEvent("onload",qx),window.attachEvent("onunload",rx));z("yt.abuse.player.botguardInitialized",B("yt.abuse.player.botguardInitialized")||Zv);z("yt.abuse.player.invokeBotguard",B("yt.abuse.player.invokeBotguard")||$v);z("yt.abuse.dclkstatus.checkDclkStatus",B("yt.abuse.dclkstatus.checkDclkStatus")||Tv);z("yt.player.exports.navigate",B("yt.player.exports.navigate")||px);
z("yt.util.activity.init",B("yt.util.activity.init")||sq);z("yt.util.activity.getTimeSinceActive",B("yt.util.activity.getTimeSinceActive")||vq);z("yt.util.activity.setTimestamp",B("yt.util.activity.setTimestamp")||tq);}).call(this);
