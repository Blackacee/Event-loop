# Event-loop

<!DOCTYPE html>
<title>Event loop example</title>
<script>
console.log("this a script entry point");
document.body.onclick = () => {
 console.log("onclick");
};
setTimeout(() => {
 console.log("setTimeout callback log 1");
 console.log("setTimeout callback log 2");
}, 100);
</script>
