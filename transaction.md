

CREATE TABLE transactions
    (id_transaction int NOT NULL PRIMARY KEY AUTO_INCREMENT,
    id_customer int,
    Id_product int,
    FOREIGN KEY (id_customer) REFERENCES customers(id_customer),
    FOREIGN KEY (Id_product) REFERENCES products(Id_product));
