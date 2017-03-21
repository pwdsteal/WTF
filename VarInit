
public class VarInit {
    public static void main(String[] args) {
        new Child();
        // Whats the output?
    }
}

class Child extends Parent {
    String text = "VarInit";

    Child() {
        System.out.println(text);
    }

    @Override
    protected void init() {
        System.out.println("init called");
        text = "Initialize";
    }
}

class Parent {

    Parent() {
        init();
    }

    void init() {}
}
