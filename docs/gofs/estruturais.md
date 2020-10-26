# Estruturais
<br>
<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/pattern.png">
</div>
<br>

<p align="justify">&emsp;Os GoF's estruturais solucionam de que maneira as classes e objetos são compostos para a formação de grandes estruturas.</p>

## **Histórico de Versões**
Data | Versão | Descrição | Autor(es) 
---- | ----------- | ------ | ---------
22/10/2020 | 1.0 | Adicionando Decorator | [@dansousamelo](http://github.com/dansousamelo)

## **1. Decorators**
<p align="justify">&emsp;O Decorator é um padrão de projeto estrutural, que permite acrescentar novos comportamentos a métodos de forma dinâmica. Os decorators permitem estender o funcionamento de um método.</p>
<p align="justify">&emsp;O Decorator foi utilizado para a criação de entidades, onde conseguimos conectá-las ao nosso banco de dados, como podemos ver logo abaixo:
</p>

~~~javascript
import {
  Entity,
  Column,
  PrimaryGeneratedColumn,
  CreateDateColumn,
  UpdateDateColumn,
} from 'typeorm';

@Entity('users')
class User {
  @PrimaryGeneratedColumn('uuid')
  id: string;

  @Column({
    length: 100,
  })
  name: string;

  @Column({
    length: 100,
  })
  email: string;

  @Column({
    length: 100,
  })
  cpf: string;

  @Column({
    length: 100,
  })
  operating_day: string;

  @Column({
    length: 100,
  })
  password: string;

  @Column({
    length: 100,
  })
  business_area: string;

  @Column()
  avatar: string;

  @Column({
    length: 100,
  })
  business_name: string;

  @Column({
    length: 100,
  })
  initial_hour: Date;

  @Column({
    length: 100,
  })
  finish_hour: Date;

  @CreateDateColumn()
  created_at: Date;

  @UpdateDateColumn()
  updated_at: Date;
}

export default User;

~~~

## **Referências**

 * <p align="justify">Erich Gamma, Richard Helm, Ralph Johnson, John Vlissides (1994). Design Patterns: Elements of Reusable Object-Oriented Software</p>